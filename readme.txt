=== Easy Support Videos - Embed videos in the admin ===
Contributors: slocumstudio
Donate link:
Tags: videos, support, youtube, vimeo, wistia, admin help, dashboard
Requires at least: 4.3
Tested up to: 4.7.2
Stable tag: 1.0.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Easy Support Videos for embedding helpful tutorials, training videos, and screencasts in the Admin dashboard. Works with YouTube, Vimeo, Wistia, VideoPress, and more!


== Description ==

Easy Support Videos is great for WordPress consultants, trainers, and product owners to embed compatible oEmbed video into the admin dashboard of a WordPress website. Simply install the plugin, and copy/paste the video link into the admin page, and Easy Support Videos will elegantly display a list of videos for your user.

https://www.youtube.com/watch?v=Tib2ouPAIEU

Admins can control who can see the videos, and edit/remove videos, by setting the available role options within Easy Support Video settings. You can also leave a custom note on the video page sidebar, offering further instructions or helpful tips.

Easy Support Videos is perfect for supporting your client or website user, through the use of videos and screencasts available on the web.

**Features**

* Great plugin for WordPress trainers, educators, and support people
* Fast & lightweight
* Embed videos in the Admin screen with ease
* Control which role's can see or edit videos
* Leave a custom note or message on the video page
* Embed videos from any oEmbed source

> **Pro Features**
>
> * White-label branding
> * Drag-n-drop video sorting
> * Create many video pages
> * Change admin link placement
> * Remove the ratings slug
> * **[Get Easy Support Videos Pro](https://slocumthemes.com/wordpress-plugins/easy-support-videos/?utm_source=easy-support-videos&utm_medium=link&utm_content=wp-org-readme-upgrade&utm_campaign=easy-support-videos)**

[View Easy Support Videos on Github](https://github.com/sdsweb/easy-support-videos/) | [Issue Tracker](https://github.com/sdsweb/easy-support-videos/issues/)


== Installation ==

1. Upload Easy Support Videos to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Browse to the Easy Support Videos page in the Admin sidebar
4. Paste any oEmbed video link into the 'Add New Video' field and press enter
5. Build a playlist of videos to support your customer or website user
6. Enjoy!


== Frequently Asked Questions ==

= How do I add a video? =

Simply paste a support oEmbed video link into the add video field, and press enter.

= What videos do you support? =

Any oEmbed compatible video. YouTube, Vimeo, Wistia, VideoPress, WordPress.tv and more.

= What if I don't want users to delete a video? =

In the settings page of Easy Support Videos, you can control who can edit and view videos based on WordPress role.


== Screenshots ==

1. Easy Support Videos
2. Easy Support Videos Options

== Changelog ==

= 1.0.3 // February 20 2017 =
-------------------------
* Fixed a bug where the sidebar message content was set to a previous value while a user was still entering content due to the AJAX save request being executed
* Updated readme

= 1.0.2 // February 15 2017 =
* Fixed issue where an AJAX spinner icon was adding extra height to video container element
* Introduced an AJAX queue to allow for AJAX requests to be queued in order of their execution
* Added logic to allow a single AJAX spinner icon to be set to inactive
* Added current_user_can() data to localized data
* Added JavaScript logic to check if the current user can edit videos before initializing various data
* Added default page title property to Easy_Support_Videos_Post_Types class
* Added flag to determine when Easy Support Videos options were saved from the Easy Support Videos Options page
* Added logic to ensure the uninstall data option was preserved when Easy Support Videos options were not saved via the Easy Support Videos Options page
* Introduced Easy_Support_Videos_Upgrade PHP class to facilitate upgrades to plugin data
* Added logic to upgrade all Easy Support Videos videos post content to the video URL instead of the oEmbed HTML markup; Fixes bug with multisite WordPress instances where administrators could not save video content; Thanks @plentyland
* Adjusted CSS for Easy Support Videos options page

= 1.0.1 // November 18 2016 =
* Added logic to only create/output nonce fields if the current user can edit Easy Support Videos videos
* Transitioned sidebar items to templates
* Added Easy_Support_Videos_View JavaScript BackboneJS view to global instances scope
* Added videos_el_selector parameter to Easy_Support_Videos_View
* Added jQuery triggers after AJAX requests
* Added page title parameter to Easy_Support_Videos_Post_Types
* Added query arguments parameter to Easy_Support_Videos_Post_Types
* Added filters to each parameter of add_menu_page()
* Added actions to UnderscoreJS template for newly added videos (matches PHP logic)
* Added actions before and after various AJAX function calls

= 1.0.0 // October 17 2016 =
* Initial Release


== Upgrade Notice ==


== Other Notes ==


= Features =

* Great plugin for WordPress trainers, educators, and support
* Fast & lightweight
* Embed videos in the Admin with ease
* Control which role's can see or edit videos
* Leave a custom note or message on the video page
* Embed videos from any oEmbed source


= Issues/Bugs =

Please report any issues or bugs on the [GitHub Issue Tracker](https://github.com/sdsweb/easy-support-videos/issues/).