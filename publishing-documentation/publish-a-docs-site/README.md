---
description: Publish your documentation to the internet as a docs site
icon: globe
---

# Publish a docs site

Once you’ve finished writing, editing, or importing your content, you can publish your work to the web as a docs site. Your docs will be published on the web and available to your selected audience.

The content on your site comes from [spaces](../../creating-content/content-structure/space.md) in your organization. When you create a new docs site, you can create a new space, or link an existing one.

<figure><img src="../../.gitbook/assets/25_12_10_publishing_documentation_publish_docs@2x.png" alt="A GitBook screenshot showing the docs sites homepage"><figcaption><p>GitBook's docs sites homepage.</p></figcaption></figure>

### Create a docs site

To create a docs site, click the plus **+** icon next to Docs site in the sidebar to launch the docs site wizard.

Give your site a name, choose a starting point for your content, and select whether you want to publish your site now or later.

If you already have content in a space that you would like to use, you can create a docs site directly from that space by opening the space and clicking **Share** in the top-right corner of the window. Then choosing **Publish as a docs site** from the share modal.

### Publish a docs site

By default, your site will be published publicly. You can change your site’s visibility in your [site’s settings](../site-settings.md).

There are three primary options to choose from when publishing your site:

<table data-view="cards"><thead><tr><th></th><th></th><th></th><th data-hidden data-card-cover data-type="image">Cover image</th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden data-type="image">Cover image (dark)</th><th data-hidden data-type="image">Cover image (dark)</th><th data-hidden data-card-cover-dark data-type="image">Cover image (dark)</th></tr></thead><tbody><tr><td><strong>Public</strong></td><td>Publish your docs publicly to the web.</td><td></td><td><a href="../../.gitbook/assets/25_12_12_public.png">25_12_12_public.png</a></td><td><a href="public-publishing.md">public-publishing.md</a></td><td><a href="../../.gitbook/assets/25_12_12_public_1.png">25_12_12_public_1.png</a></td><td></td><td><a href="../../.gitbook/assets/25_12_12_public_1.png">25_12_12_public_1.png</a></td></tr><tr><td><strong>Privately with share links</strong></td><td>Publish your docs with private share links.</td><td></td><td><a href="../../.gitbook/assets/25_12_12_share_links_1.png">25_12_12_share_links_1.png</a></td><td><a href="share-links.md">share-links.md</a></td><td></td><td><a href="../../.gitbook/assets/25_12_12_share_links.png">25_12_12_share_links.png</a></td><td><a href="../../.gitbook/assets/25_01_06_share_links@2x.png">25_01_06_share_links@2x.png</a></td></tr><tr><td><strong>Authenticated Access</strong></td><td>Protect your published docs behind an OAuth sign in.</td><td></td><td><a href="../../.gitbook/assets/25_12_10_auth_access_1.png">25_12_10_auth_access_1.png</a></td><td><a href="../authenticated-access/">authenticated-access</a></td><td></td><td></td><td><a href="../../.gitbook/assets/25_12_10_auth_access.png">25_12_10_auth_access.png</a></td></tr></tbody></table>

### Delete or unpublish a docs site

To delete a docs site, you’ll need to open your site’s dashboard, then open [**Site settings**](../site-settings.md#delete-site) from the top-right corner.

### Site permissions

Admins can manage site permissions directly from a docs site.

From the site’s **Overview** page, click **Share** in the top-right corner. You can also open **Settings** > **General** and click **Access** > **Manage permissions**.

You can also manage these settings from [Site settings](../site-settings.md).

Setting a permission level on a site, for everyone, a team, or an individual user, determines their ability to administer or view the site. When spaces within the site are set to _**Inherited**_ mode, these permissions are also propagated to those spaces.

The table below summarizes how each role maps to permissions on the site and how it propagates to spaces in _**Inherited**_ mode.

| Permission level for spaces | Permissions on the site |
| --------------------------- | ----------------------- |
| Administrator               | Edit and see            |
| Creator                     | See                     |
| Reviewer                    | See                     |
| Editor                      | See                     |
| Commenter                   | See                     |
| Viewer                      | See                     |
| No access                   | Cannot see              |

{% hint style="info" %}
Spaces in _**Inherited**_ mode inherit permissions from the organization or their parent collection, along with the site permissions and any local overrides.

Each member is assigned the highest role they have across these permission sources.
{% endhint %}
