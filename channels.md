Site Channels (summary) What it is: Site Channels wires a GitBook site to Slack and GitHub so people can talk to GitBook’s bot in those places. When someone @mentions the bot (or continues in a thread the bot already joined), the service answers using site-aware AI (content scope, tools, optional MCP), not a generic chatbot.

How it runs: A Cloud Run service (site-context-channels) is exposed under /channels on the sites host. It handles:

Webhooks — POST /platforms/:platform/webhook forwards each platform’s events into a shared Chat instance with per-platform adapters (slack, github) and Redis-backed thread state. OAuth — install/authorize flows per platform so the app can post and read in the right workspace/repo context. Request path (conceptually): Incoming event → platform adapter normalizes it → the bot looks up which site channel this maps to (via external IDs and the siteChannels DB rows) → it loads AI inputs, site content scope, and MCP config → it streams a reply back on the same thread (streamAIMessage + channel-specific streaming). Platform hooks can run at start/end of a reply. Reactions on support-style channels can be recorded as thumbs-up/down style feedback.

Setup: Each environment needs the corresponding Slack/GitHub app config (webhook URL, OAuth callback, secrets) as described in services/context/channels/README.md.
