=== Sermon Embed ===
Contributors: eriktdesign
Tags: embed, sermon, audio, church
Requires at least: 3.0.1
Tested up to: 5.7
Stable tag: 1.2.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
 
A WordPress plugin for automatic embedding of content from Faithlife Sermons (formerly SoundFaith)
 
== Description ==
 
Faithlife Sermons (formerly SoundFaith.com) is a great site to host your recorded sermons, especially when used with the Proclaim presentation software. The plugin allow you to easily embed individual sermons or a playlist of sermons on your WordPress website without using any code.

## Usage

### Share an individual sermon

1. Copy the URL from your sermon on sermons.faithlife.com, eg: <https://sermons.faithlife.com/sermons/245351-this-is-my-commandment>
2. Edit the post or page where you want to embed the sermon.
3. Paste the URL on a line by itself in the editor or as the URL of an *Embed* block
4. Presto! The URL will turn into an embedded player for your sermon.

### Share a profile

1. Copy the URL of your Faithlife Sermons profile page
2. Edit the post or page where you want to embed the profile
3. Paste the URL on a line by itself in the editor or as the URL of an *Embed* block
4. Another presto! Your URL will turn into the most recent sermons playlist.

### Share a series

1. Copy the URL of the series page
2. Edit the post or page where you want to embed the sermon series
3. Paste the URL on a line by itself in the editor or as the URL of an *Embed* block
4. Presto again! The URL will turn into a playlist with sermons from the series. 

## Settings

The plugin settings page under _Settings->SoundFaith Embed_ contains the same settings available under the "Embed" dialog on SoundFaith.com

---

_I have no affiliation with Faithlife. I built this plugin because I needed an easier way to embed sermons for the preaching staff at my church. Enjoy!_
 
== Installation ==
 
1. Upload to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Edit the settings under _Settings->Sermon Embed_
1. Embed sermons or playlists by pasting the URL in a post
 
== Frequently Asked Questions ==
 
= How can I change the width of my embedded sermons? =
 
The embedded player size is calculated with your theme's `$content_width` variable. If your theme doesn't have this set, the embed will default to 600px wide. [Learn more in the Codex](https://codex.wordpress.org/Content_Width).
 
= How do I customize what metadata are included in the embed? =

Go to _Settings->Sermon Embed_ and select which metadata you'd like included. These mirror the embed options found on Faithlife Sermons.
 
== Screenshots ==
 
1. Sermon Embed settings page
 
== Changelog ==

= 1.2.2 =
* Update plugin name
* Tested up to WordPress 5.7
* Update references to SoundFaith throughout the plugin to Faithlife Sermons.

= 1.2.1 = 
* Change language in readme

= 1.2.0 = 
* SoundFaith is now Faithlife Sermons
* Add sermons.faithlife.com to embed regex
* Change embed URL to use sermons.faithlife.com. 

= 1.1.0 =
* Add support for embedding a sermon series
* Check compatibility for WordPress 4.9

= 1.0.3 =
* Check compatibility for WordPress 4.8

= 1.0.2 =
* Properly get the `$content_width`
 
= 1.0.1 =
* Fix debug error

= 1.0.0 =
* Release on WordPress.org

= 0.2.0 =
* Add settings page
 
= 0.1.0 =
* Initial version
 
== Upgrade Notice ==

= 1.0.2 =
This version fixes a bug where the theme's `$content_width` was ignored

= 1.0.1 =
Fixes an error in `wp_footer`
 
= 1.0.0 =
This is the first version.