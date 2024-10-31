=== Remove WP Version ===
Contributors: marziocarro, gattowp
Tags: wordpress version, generator, security, meta, remove version, remove wordpress version, remove wp version, remove generated, remove generator, hide version, hide wordpress version, hide wp version, meta generator
Requires at least: 3.0
Tested up to: 5.3
Stable tag:trunk
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Removes the meta generator tag, with WordPress version from HTML.

== Description ==

Removes the meta generator tag, with WordPress Version.

A simple plugin to prevent people from knowing what version of Wordpress you're using via your HTML source.


This is a very simple plugin. You can get the same thing by adding this line to funcions.php file of your theme:

remove_action('wp_head', 'wp_generator');


But if you're not comfortable editing a php file, you can use this plugin to remove the WordPress version from your HTML.

The plugin has no settings and does not alter the database.


**Plugin's website:** <a href="https://www.gattowp.com/">https://www.gattowp.com/</a>

**Author's website:** <a href="http://technotes.marziocarro.com/">http://technotes.marziocarro.com/</a>

== Installation ==

1. Copy the `remove-wp-version` directory into your WordPress plugins directory (usually wp-content/plugins).

2. In the WordPress Admin Menu go to the Plugins tab and activate the 'Remove WP Version' plugin.

== Screenshots ==

Nothing to see, no settings, no options.

== Changelog ==

= 1.0 =

initial release

== Upgrade Notice ==

No upgrade notices so far...

== Frequently Asked Questions ==

None yet
