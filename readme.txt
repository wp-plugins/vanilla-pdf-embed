=== vanilla-pdf-embed ===
Contributors: _doherty
Tags: pdf, embed
Donate link: https://flattr.com/profile/doherty
Requires at least: 3.0.1
Tested up to: 3.6
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Embeds PDFs in your pages and posts, without using JS.

== Description ==
To embed a PDF you've uploaded to your Wordpress site's media
library, simply put the URL for the attachment page in your
post on its own line. The PDF will be embedded with the
default settings at that location, as if it were using oEmbed.

If the PDF isn't in your Wordpress site's media library, or if
you want to customize any parameters for the embed, then use
the `[pdf]...[/pdf]` short tag. Between the tags, you'll provide
the URL for the PDF to embed. If the PDF is in your Wordpress
site's media library, you can either give the attachment page
URL, or the URL to the PDF file directly.

== Installation ==
1. Upload `vanilla-pdf-embed.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the "Plugins" menu in the WordPress admin panel

== Changelog ==

= 0.0.2 =
  - Don't embed non-PDFs from the media library

= 0.0.1 =
  - Initial release
