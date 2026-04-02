# Roles

When adding members to your organization, you can give them a **default role**. This role will apply to any content that inherits its permissions from the organization.

{% hint style="info" %}
Understanding default roles is key to getting the most out of how GitBook handles permission management.&#x20;

See our documentation on [**permissions and inheritance**](permissions-and-inheritance.md) for a full overview of how permissions cascade throughout content in GitBook.
{% endhint %}

### Roles in GitBook

Roles are how you define the level of access and control that members have over content (and the organization, in the case of admins).

{% hint style="warning" %}
Regardless of role, _**every**_ _**single member**_ of an organization _**counts towards**_ the total number of members for _**billing**_ purposes.\
\
You might also like to learn more about [inviting and removing members](invite-members-to-your-organization.md).
{% endhint %}

Each role gets progressively higher levels of access as you move up the list. This list starts at the lowest access level, with extra features above the previous access level highlighted in bold.

<details>

<summary>Reader</summary>

A reader is the most basic role in GitBook. Readers get read-only access, so they can:

* Read content in your organization.

**Reader seats are paid for organizations on all plans**.&#x20;

</details>

<details>

<summary>Commenter</summary>

Commenters can:

* Read content in your organization (read-only access).
* **Leave** [**comments**](../../collaboration/comments.md) **on your organization’s content within** [**spaces**](../../creating-content/content-structure/space.md)**.**

{% hint style="info" %}
Commenter is one of our two advanced member roles, available only on the Pro or Enterprise plan.
{% endhint %}

</details>

<details>

<summary>Editor</summary>

Editors can:

* Read content in your organization.
* Leave [comments](../../collaboration/comments.md) on your organization’s content within [spaces](../../creating-content/content-structure/space.md).
* **Directly edit spaces that have** [**live edits**](../../collaboration/live-edits.md) **unlocked.**&#x20;
* **Create** [**change requests**](../../collaboration/change-requests.md) **to edit spaces with** [**locked live edits**](../../collaboration/live-edits.md)**.**
* [**Request a review**](../../collaboration/change-requests.md#request-a-review-on-a-change-request) **on a change request.**

Editors **cannot** merge change requests.

</details>

<details>

<summary>Reviewer</summary>

Reviewers have all the same permissions as an editor, with one important addition — the ability to merge change requests. Reviewers can:

* Read content in your organization.
* Leave [comments](../../collaboration/comments.md) on your organization’s content within [spaces](../../creating-content/content-structure/space.md).
* Directly edit spaces that have [live edits](../../collaboration/live-edits.md) unlocked.&#x20;
* Create [change requests](../../collaboration/change-requests.md) to edit spaces with [locked live edits](../../collaboration/live-edits.md).
* [Request a review](../../collaboration/change-requests.md#request-a-review-on-a-change-request) on a change request.
* **Review and merge change requests.**

{% hint style="info" %}
Reviewer is one of our two advanced member roles, available only on the Pro or Enterprise plan.
{% endhint %}

</details>

<details>

<summary>Creator</summary>

Creators are essentially content-level admins. Creators can:

* Read content in your organization.
* Leave [comments](../../collaboration/comments.md) on your organization’s content within [spaces](../../creating-content/content-structure/space.md).
* Directly edit spaces that have [live edits](../../collaboration/live-edits.md) unlocked.&#x20;
* Create [change requests](../../collaboration/change-requests.md) to edit spaces with [locked live edits](../../collaboration/live-edits.md).
* [Request a review](../../collaboration/change-requests.md#request-a-review-on-a-change-request) on a change request.
* Review and merge change requests.
* **Create, manage and delete spaces,** [**collections**](../../creating-content/content-structure/collection.md) **and** [**docs sites**](../../publishing-documentation/publish-a-docs-site/)**.**
* **Manage** [**permissions**](permissions-and-inheritance.md) **at a content level.**

</details>

<details>

<summary>Administrator</summary>

Admins are like super-users for your organization — they have full access! Admins can:

* Read content in your organization.
* Leave [comments](../../collaboration/comments.md) on your organization’s content within [spaces](../../creating-content/content-structure/space.md).
* Directly edit spaces that have [live edits](../../collaboration/live-edits.md) unlocked.&#x20;
* Create [change requests](../../collaboration/change-requests.md) to edit spaces with [locked live edits](../../collaboration/live-edits.md).
* [Request a review](../../collaboration/change-requests.md#request-a-review-on-a-change-request) on a change request
* Review and merge change requests.
* Create, manage and delete spaces, [collections](../../creating-content/content-structure/collection.md) and [docs sites](../../publishing-documentation/publish-a-docs-site/).
* Manage [permissions](permissions-and-inheritance.md) at a content level.
* **Manage member roles within the organization.**
* **Access billing settings for updates to payment details.**
* **Control organization settings and configuration.**

Set someone as an admin if you’re comfortable with them making changes that can impact billing, managing members, and generally just being in control of all areas of the organization.

</details>

### The guest role

The guest role is a very specific role in GitBook with permissions set at a content level.

[Inviting a guest](../../collaboration/share.md#invite-someone-from-outside-your-organization) is great if you want to share only specific content with external stakeholders or contractors for review or feedback, without giving them access to any other content in your organization.

Guests members have **no default organization role**. That means they won’t be able to access any content in your organization, unless it’s directly shared with them. A guest acts as a standard user in every other regard, but with permissions set at a content level.

**Please note that guest members, as with all other members, count towards the total number of members in an organization for billing purposes.**
