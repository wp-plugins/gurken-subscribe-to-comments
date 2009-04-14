=== Subscribe to Comments ===
Tags: comments, subscription, email
Contributors: infogurke
Donate link: http://www.infogurke.de
Requires at least: 2.0.6
Tested up to: 2.7
Stable tag: trunk

Subscribe to Comments with Double-Opt-In

== Description ==

Based on "Subscribe to Comments" from Mark Jaquith.

Gurken Subscribe To Comments enables you to sign up for email notification of
subsqeuent entries, with Double-Opt-In.

Features:
- All of the original Subscribe to Comments
- Registration with Double-Opt-In
- Multi-Language (English or German)
- heavily tested ;-)

== Installation ==

1. Download & unpack into [wordpress_dir]/wp-content/plugins/
2. Go into the WordPress admin interface and activate the plugin
3. Optional: if your WordPress theme doesn't have the comment_form hook, or if you would like to manually determine where in your comments form the subscribe checkbox appears, enter this where you would like it: `<?php show_subscription_checkbox(); ?>`
4. Optional: If you would like to enable users to subscribe to comments without having to first leave a comment, place this somewhere in your template, but make sure it is **outside the comments form**.  A good place would be right after the ending `</form>` tag for the comments form: `<?php show_manual_subscription_form(); ?>`

== Frequently Asked Questions ==

Be free to ask ;-)

