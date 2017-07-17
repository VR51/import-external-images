=== Import External Images VR51 ===

Makes local copies of all externally linked images and (Optionally) PDFs in a post.

== Description ==

Imports images and (optionsally) PDFs from external sites where external images are referenced within a post.

= Features =

= Credits =

This plugin is based on the work done in the "Add Linked Images to Gallery" plugin by http://www.bbqiguana.com/

Version 1.5 is a bugfix release by [VR51](https://github.com/VR51/import-external-images).

== Installation ==

1. Download the "Import External Images" zip file.
2. Upload to your WordPress plugins directory.
3. Activate the plugin via the WordPress Plugins tab.
4. Navigate to Media > Import Images or edit a post to import externally linked media.

== Frequently Asked Questions ==

= How does this plugin work? =

This plugin will find IMG attachments or PDF attachments within posts and pages. Any external attachments will be brought into downloaded to your site's media library and their links in posts/pages will be changed to those of your own website.

= Does it work with MultiSite? =

Yes!

= What if i don't want to import images from a third party image hosting site? =

You can make it ignore any domain you want on the settings page, in case you work with a CDN or photo hosting site and want to keep those images where they are.

== Changelog ==

= 1.5.1 =

- Improved posts layout table.
- Various code changes.

= 1.5 =


This is the first VR51 release of this plugin.

- Fixed bug that caused the plugin to download images hosted on HTTP sites. Now fetches imedia from HTTPS sites too.
- Changed post query to explicitly loop through all post types with any post status.
- Added option to import externally linked PDFs.
- Fixed undefined variable error.
- Fixed undefined key error.
- Changed link of Bulk Image Resizer plugin to Regenerate Thumbnails hosted on wordpress.org.
- Added option to adjust number of images to process per run.
- Added option to adjust number of posts to process per run.

= 1.3 =

- Fixed case sensitivity, thanks to https://github.com/SidFerreira
- Fixed duplicate EXTERNAL_IMAGES_DIR notice

= 1.1 =

- Fixed title in readme.
