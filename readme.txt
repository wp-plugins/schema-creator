=== Schema Creator by Raven ===
Contributors: norcross, raventools
Tags: schema.org, microdata, structured data, seo, html5
Tested up to: 3.4.2
Stable tag: 1.030
Requires at least: 3.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Insert schema.org microdata into WordPress pages and posts.

== Description ==

Provides an easy to use form to embed properly constructed schema.org microdata into a WordPress post or page.

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload `schema-creator` to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.

== Frequently Asked Questions ==

= How does this all work? =

The Schema Creator plugin places an icon above the Post/Page rich text editor (next to the Add Media icon). Click on the icon to select a supported schema, fill in the form, and then insert it into your page/post. The plugin uses shortcode, so you can easily edit the schema after you create it. There are additional options on the Schema Creator Settings page.

= Can I test the output to see how the search engine will view it? =

Yes, although there is no guarantee that it will indeed show up that way. Google offers a [Rich Snippet Testing tool](http://www.google.com/webmasters/tools/richsnippets/ "Google Rich Snippet Test") to review.

= I have a problem. Where do I go? =

This plugin is also maintained on [GitHub](https://github.com/norcross/schema-creator/ "Schema Creator on GitHub"). The best place to post questions / issues / bugs / enhancement requests is on the [issues page](https://github.com/norcross/schema-creator/issues "Issues page for Schema Creator on GitHub") there.


== Screenshots ==

1. The plugin creates a Schema Creator icon above the rich text editor. Click the icon to create a new schema.
2. Choose the schema you want to create from the select menu and then enter the data. Once you're finished, insert it into your post or page.
3. Schema Creator creates shortcode, which enables you to edit the schema after it's created.
4. This is an example of schema being rendered on a post.
5. Schema Creator also has a Settings page.
6. The Settings page allows you to turn on and off CSS, and to also include or exclude certain microdata attributes.

== Upgrade Notice ==

= 1.0 =
* Initial Release

== Changelog ==

= 1.030 =
* bumped version number to fix update quirk

= 1.023 =
* bugfix for HTML entities in schema descriptions
* metabox option to disable itemprop & itemtype on a post by post basis
* change to the readme and instructions page to include a link to the Google Rich Snippet testing page

= 1.022 =
* replacing body tag method from JS to using core WP functionality.

= 1.021 =
* loading JS for body tag in head

= 1.02 =
* update to logic for loading itemprop body tags and content wrapping

= 1.01 =
* minor bugfix

= 1.0 =
* Initial Release
