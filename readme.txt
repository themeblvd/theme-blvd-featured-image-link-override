=== Theme Blvd Featured Image Link Override ===
Contributors: themeblvd
Tags: themeblvd, featured images, thumbnails, links, filo
Requires at least: Theme Blvd Framework 2.1+
Stable tag: 2.0.4

When using a theme with Theme Blvd framework version 2.1+, this plugin allows you to set featured image link options globally throughout your site.

== Description ==

When using a theme with Theme Blvd framework version 2.1+, this plugin allows you to set featured image link options globally throughout your site.

= The Problem =

The Theme Blvd framework has an intricate internal system for displaying posts and their respective featured images. You can choose from many different options as far as what link wraps each post's featured image. However, this can only be done individually for each post. By default, when you create a new post, this setting will always start at "Featured Image is not a link."

This is a problem if you're creating a site where you want all featured images to do one action because then you'd have to change the "Featured Image Link" setting for each post you create, one-by-one. Unfortunately, with the logic of the framework the way it is, there's really no good way for us to accommodate this without losing other aspects.

= The Solution =

So, this plugin is your solution -- a bit of a "hack" to allow you do to accomplish this. When you install the plugin, two new options will be added to your Theme Options at *Appearance > Theme Options > Configuration*.

The two options will apply to **ALL** of your posts that currently have the default setting, "Featured Image is not a link." -- See screenshots tab for a quick peak.

== Installation ==

1. Upload `theme-blvd-featured-image-link-override` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to *Appearance > Theme Options > Configuration* to use.

== Screenshots ==

1. Options added to your current theme at *Appearance > Theme Options > Configuration*.

== Changelog ==

= 2.0.4 - 12/15/2016 =

* Fixed: Link overriding not working after updating to WordPress 4.7.

= 2.0.3 - 12/31/2015 =

* Fixed: There were some issues in some themes with the first post in certain situations not getting the image link override setting.

= 2.0.2 - 12/16/2015 =

* Fixed: Featured image link override should only get applied if the user hasn't set one on the current post already.

= 2.0.1 - 12/15/2015 =

* Fixed: Make sure meta data filtering only happens on frontend to avoid admin errors.

= 2.0.0 - 12/15/2015 =

* Improvement: Frontend functionality was re-written to filter the meta data of posts, opposed to the actual featured images. As more Theme Blvd themes and updates are released, this will ensure better compatibility for the long haul.
* Improvement: Simplified presence on Theme Options page.

= 1.0.7 - 10/20/2015 =

* Fixed: Featured image override shouldn't effect attachment pages.

= 1.0.6 - 08/04/2015 =

* Fixed: Post showcase thumbnails not showing post titles (Theme Blvd Framework 2.5+ themes).
* GlotPress compatibility (for 2015 wordpress.org release).

= 1.0.5 - 02/15/2015 =

* Compatibility for Theme Blvd Framework 2.5+.

= 1.0.4 - 08/04/2013 =

* Fixed Configuration options not showing on Theme Options page for Theme Blvd Framework 2.3+.
* Fixed lightbox functionality for Theme Blvd Framework 2.3+.

= 1.0.3 - 12/24/2012 =

* Added thumbnail styling classes used in Theme Blvd framework v2.2+.

= 1.0.2 - 08/29/2012 =

* Added in ability to override featured image links for posts never saved with the Theme Blvd theme active.

= 1.0.1 - 08/29/2012 =

* Fixed bug with override being applied when it shouldn't be.

= 1.0.0 - 06/03/2012 =

* This is the first release.
