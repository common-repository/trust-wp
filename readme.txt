=== Trust WP ===
Contributors: rrpathi
Tags: login, wp-login.php, custom login,security,trust,rename,attack
Requires at least: 3.1
Tested up to: 5.6.1
Stable tag: trunk

== Description ==

Trust WP is a very light plugin that lets you easily and safely change wp-login.php to anything you want. It doesn’t literally rename or change files in core, nor does it add rewrite rules. It simply intercepts page requests and works on any WordPress website. 

The wp-admin directory and wp-login.php page become inaccessible, so you should bookmark or remember the url. Deactivating this plugin brings your site back exactly to the state it was before.

== Frequently Asked Questions ==

I forgot my login url!

Either go to your MySQL database and look for the value of wps_page in the options table, or remove the trust-wp folder from your plugins folder, log in through wp-login.php and reinstall the plugin.

On a multisite install the wps_page option will be in the sitemeta table, if there is no such option in the options table.

== Changelog ==

= 1.0.0  - 25th Feb 2021 =
* Initial version ♡. This is a fork of the Rename wp-login.php plugin, which is unmaintained https://wordpress.org/plugins/rename-wp-login/. All previous changelogs can be found there.