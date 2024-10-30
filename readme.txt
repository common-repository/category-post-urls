=== Category Post URLs ===

Contributors: maheshkathiriya
Tags: rewrite rules, category post urls, custom permalink, category and subcategory permalink, category post urls
Requires at least: 3.0
Tested up to: 4.8.2
Stable tag: 0.01
License: GPLv2 or later

Add Category and Subcategory in Wordpress Post URLs, Set a hierarchical URLs like nested sub category : 
<code>category-name/sub-category-name/sub-category-name/year/month/day/post-slug</code> for all post
types and taxonomies.

== Description ==
Category and Subcategory in WordPress Post URLs. Enables Category Post URLs, making posts follow categories and parent categories and sub categories
to define their permalink. Assume a blog with the following category structure
for posts:

* News
  - Marvel
  - Game
* Review
  - DC Review
  - Popular Movie Review

By default, their URLs will be <code>category/%sub-category-name%</code>. Activating this
plugin will end up in URLs like:

* News: `news`
  - Marvel: `news/marvel`
  - Game: `News/game`
* Review `review`
  - dc-review: `review/dc-review`
  - popular-movie-review: `review/popular-movie-review`

For posts inside the Italian food category, for example, the URL will be
<code>review/popular-movie-review/%year%/%monthnum%/%day%/%postname%</code>.

== Installation ==

Upload the plugin to your `wp-content/plugins` and activate it.

== TODO ==

* Flush rules on term creating
* Reflect post URL in the admin slug edit section

== Changelog ==

= 0.01 =

* First version with some functional code.
