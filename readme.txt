=== Conditional Links ===

Description:	The cpl shortcode allows links to be generated when the page exists; allows index or other pages to be built before child or other linked pages. Adds anchor tags to valid links otherwise outputs plain text.
Version:		1.2.1
Tags:			page, pages, post, posts, link, shortcode
Author:			azurecurve
Author URI:		https://development.azurecurve.co.uk/
Plugin URI:		https://development.azurecurve.co.uk/classicpress-plugins/conditional-links/
Download link:	https://github.com/azurecurve/azrcrv-conditional-links/releases/download/v1.2.1/azrcrv-conditional-links.zip
Donate link:	https://development.azurecurve.co.uk/support-development/
Requires PHP:	5.6
Requires:		1.0.0
Tested:			4.9.99
Text Domain:	conditional-links
Domain Path:	/languages
License: 		GPLv2 or later
License URI: 	http://www.gnu.org/licenses/gpl-2.0.html

The cpl shortcode allows links to be generated when the page exists; allows index or other pages to be built before child or other linked pages. Adds anchor tags to valid links otherwise outputs plain text.

== Description ==

# Description

Conditional links allows shortcodes to be created which will automatically link when a page or blog post exists with the same slug or title. If the conditionally linked page or post exists, the text will be wrapped in anchor tags otherwise plain text will be returned.

The following shortcodes are available:
* cpl for page links.
* cbl for blog post links.

Shortcodes can be used in the following ways:
* [cpl slug="link"]
* [cpl title="this link title"]link[/cpl]
* [cpl slug="link" title="the link title"]

This plugin is multisite compatible.

== Installation ==

# Installation Instructions

 * Download the plugin from [GitHub](https://github.com/azurecurve/azrcrv-conditional-links/releases/latest/).
 * Upload the entire zip file using the Plugins upload function in your ClassicPress admin panel.
 * Activate the plugin.
 * Configure relevant settings via the configuration page in the admin control panel (azurecurve menu).

== Frequently Asked Questions ==

# Frequently Asked Questions

### Can I translate this plugin?
Yes, the .pot fie is in the plugins languages folder and can also be downloaded from the plugin page on https://development.azurecurve.co.uk; if you do translate this plugin, please sent the .po and .mo files to translations@azurecurve.co.uk for inclusion in the next version (full credit will be given).

### Is this plugin compatible with both WordPress and ClassicPress?
This plugin is developed for ClassicPress, but will likely work on WordPress.

== Changelog ==

# Changelog

### [Version 1.2.1](https://github.com/azurecurve/azrcrv-conditional-links/releases/tag/v1.2.1)
 * Update azurecurve menu and logo.
 
### [Version 1.2.0](https://github.com/azurecurve/azrcrv-conditional-links/releases/tag/v1.2.0)
 * Fix plugin action link to use admin_url() function.
 * Rewrite option handling so defaults not stored in database on plugin initialisation.
 * Add plugin icon and banner.
 * Update azurecurve plugin menu.
 * Amend to only load css when shortcode on page.

### [Version 1.1.6](https://github.com/azurecurve/azrcrv-conditional-links/releases/tag/v1.1.6)
 * Fix bugs with links to non-existent post/page showing slug instead of title or content.

### [Version 1.1.5](https://github.com/azurecurve/azrcrv-conditional-links/releases/tag/v1.1.5)
 * Fix bug with setting of default options.
 * Fix bug with plugin menu.
 * Update plugin menu css.

### [Version 1.1.4](https://github.com/azurecurve/azrcrv-conditional-links/releases/tag/v1.1.4)
 * Rewrite default option creation function to resolve several bugs.
 * Upgrade azurecurve plugin to store available plugins in options.
 
### [Version 1.1.3](https://github.com/azurecurve/azrcrv-conditional-links/releases/tag/v1.1.3)
 * Fix version number bug.

### [Version 1.1.2](https://github.com/azurecurve/azrcrv-conditional-links/releases/tag/v1.1.2)
 * Update Update Manager class to v2.0.0.
 * Update action link.
 * Update azurecurve menu icon with compressed image.

### [Version 1.1.1](https://github.com/azurecurve/azrcrv-conditional-links/releases/tag/v1.1.1)
 * Fix bug with incorrect language load text domain.

### [Version 1.1.0](https://github.com/azurecurve/azrcrv-conditional-links/releases/tag/v1.1.0)
 * Add integration with Update Manager for automatic updates.
 * Fix issue with display of azurecurve menu.
 * Change settings page heading.
 * Add load_plugin_textdomain to handle translations.

### [Version 1.0.1](https://github.com/azurecurve/azrcrv-conditional-links/releases/tag/v1.0.1)
 * Update azurecurve menu for easier maintenance.
 * Move require of azurecurve menu below security check.
 * Localization fixes.

### [Version 1.0.0](https://github.com/azurecurve/azrcrv-conditional-links/releases/tag/v1.0.0)
 * Initial release for ClassicPress forked from azurecurve Conditional Links WordPress Plugin.

== Other Notes ==

# About azurecurve

**azurecurve** was one of the first plugin developers to start developing for Classicpress; all plugins are available from [azurecurve Development](https://development.azurecurve.co.uk/) and are integrated with the [Update Manager plugin](https://codepotent.com/classicpress/plugins/update-manager/) by [CodePotent](https://codepotent.com/) for fully integrated, no hassle, updates.

Some of the top plugins available from **azurecurve** are:
* [Add Twitter Cards](https://development.azurecurve.co.uk/classicpress-plugins/add-twitter-cards/)
* [Breadcrumbs](https://development.azurecurve.co.uk/classicpress-plugins/breadcrumbs/)
* [Series Index](https://development.azurecurve.co.uk/classicpress-plugins/series-index/)
* [To Twitter](https://development.azurecurve.co.uk/classicpress-plugins/to-twitter/)
* [Theme Switches](https://development.azurecurve.co.uk/classicpress-plugins/theme-switcher/)
* [Toggle Show/Hide](https://development.azurecurve.co.uk/classicpress-plugins/toggle-showhide/)