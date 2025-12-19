# Page indexing

Page indexing is the process by which search engines collect, analyze, and add pages to their databases so they can appear in search results for relevant queries.

Some pages on your website may be excluded from indexing—this means they will not appear in search results or may soon be removed from the search engine’s index.

### What does Prevent indexing of hidden pages mean?

In the **Site settings** → **Other site settings** section, you can choose how your pages are indexed.\
By default, the **Prevent indexing of hidden pages** option is enabled. [Landing pages](../pages/landing.md) and hidden pages will not be indexed.

<figure><img src="../../.gitbook/assets/hidden page indexing en.png" alt="" width="563"><figcaption></figcaption></figure>

With this setting turned on, the following pages are always indexed:

* The main page.
* Pages that are visible in the site menu.

Other pages will be indexed if:

* They are published and located in a visible section of the site: dropdown menus, blog, announcements, or gallery.
* They are linked from a page that is visible in the menu.

### How to index a hidden page

To index a hidden page, simply link to it from a visible, menu-listed page.

For example, if your _Services_ page is visible in the menu and you have created a landing page for a new workshop, add a [button](../content/clickable-link.md#button-link) on the _Services_ page linking to that landing.

That way, the hidden page will be indexed, while other hidden pages will remain excluded.

{% hint style="info" %}
Make sure to add a [button link](../content/clickable-link.md#button-link) or an [image link](../content/clickable-link.md#image-link). Adding a text link will not affect page indexing status.
{% endhint %}

### How to index all pages on your site

To allow all pages to be indexed, disable the **Prevent indexing of hidden pages** toggle.

Before doing so, make sure your site doesn’t contain any content you don’t want showing up in search results (such as drafts, outdated pages, or incomplete content).
