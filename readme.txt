=== Media Tools  ===
Contributors: c3mdigital
Tags: media, media library, images, featured images, post thumbnails, timthumb
Requires at least: 3.1
Tested up to: 3.9 Beta
Stable tag: 1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A set of tools to help manage your media library.

Big improvements are coming to the WordPress media library in 3.5. If your not using the media library this plugin will import all the external images found in your posts or pages and import them into the media library and attach them

== Description ==

A set of tools to help manage your media library.

Big improvements are coming to the WordPress media library in 3.5. If your not using the media library this plugin will import all the external images found in your posts or pages and import them into the media library and attach them.

This plugin will help you convert from using Timthumb to WordPress built in featured image / post thumbnail support

The Tools

* Import and attach - imports and attaches all external referenced images in your posts
* Set Featured Image - finds the first attached image to post and sets it as the featured image
* Add post thumbnail support to your site
* Set additional thumbnail sizes

Control and filter the import script by post type, author, date range, or category.

Ajax interface that imports, attaches and sets featured images with one click.
Integrates with the Regenerate Thumbnails plugin to regenerate thumbnail crops based on newly selected image sizes.

Vist http://c3mdigital.com/wordpress for more plugin information.

== Installation ==

1. Upload the media-tools folder to your wp-content/plugins dir and activate through the dashboard or
2. Install or upload directly from the admin dashboard

The options and tools are located under the tools menu.

**Please Note:  Requires PHP 5.2**

== Frequently Asked Questions ==

= What does this plugin do? =

This plugin allows you to go through all your posts, pages, or custom post types and import any externally referenced images into your media library
and attaches them to the post and can even set the first image as the featured image.

It also enables post thumbnail support if your current theme does not support post thumbnails.  You can even define a custom thumbnail image size.

= I moved my website to a new domain and server and none of my images are showing in the media library or in my posts.  How can I fix this? =

If the images are still on the old server you can use this plugin to re import all of them into your media library.  You will want to first delete your
your images from the media library so it un attaches the broken links from your posts then run the import tool to re attach them and import them back into
your media library.

= Isn't it illegal to download images and show them on my website? =

If you do not have permission to use the images and or the copyright does not allow use, then yes it is a copyright violation.   It is your
responsibility to make sure you have legal right to use any images.  PLEASE DON'T USE THIS PLUGIN TO VIOLATE COPYRIGHT LAWS!

= Where can I get support for this plugin? =

For immediate support you can check the #WordPress IRC channel on irc.freenode.net and see if I'm available to help you.  Just type ping c3mdigital
and if I'm around I will be glad to help.  You can also use the WordPress support forums and I will try to answer as soon as possible.

== Screenshots ==

1. The Import and Attachment Tools
2. The Add additional image sizes options page

== Changelog ==

= 1.1 =

* Added progress bar to show status of importer tools
* Img status for each post now updates as the importer is running
* Separate ajax call for each post to prevent time outs
* Better error handling and messages
* Minor bug fixes

= 1.0.1 =

* Added WordPress and PHP version checks
* Improved file upload error handling
* Improved responses from the media tools
* Small bug fixes and improvements
* Better procedure for checking if image is already attached to post

= 1.0 =

* Initial version added to WordPress.org

== Upgrade Notice ==

= 1.1 =

Please Upgrade for better image error handling and new progress bar

= 1.0.1 =

Please update to this version.  Numerous bug fixes and improvements. See changelog for more details.