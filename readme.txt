=== WP Bots Analytics ===
Contributors: Giuseppe PastoreDonate link: http://www.giuseppepastore.com/
Tags: spiders, google, analytics, seo
Requires at least: 2.7
Tested up to: 4.0.1
Stable tag: 4.0
Enables tracking bots via google analytics on all pages.

== Description ==

This plugin enables **tracking spiders and bots via Google analytics** without harc-coding your template files. Tracking bots and spiders on your website can help you understanding if all pages are visited by search engines or some of them have crawling problems. It is also useful to conduct SEO tests, if have not access to your server logs.

In order to make this plugin work, you need 2 thing:

1. A **new profile** within your Google Analytics account. Select a "Add a Profile for a new domain". Name it as you like (I suggest bots.mydomain.com). Take note of the **Web Property ID** (UA-XXXXXX-YY).

1. The Google identifier of your domain, that's the value of your **_utma cookie** on your website. Yo find this, use Mozilla Firefox (Tools>> Options>>> Show Cookies). Find your site, expand and look for the cookie named "_utma" (look at the first screenshot).

Once you have this informations, you can install and activate the plugin.

For more information visit: [WP Bots Analytics Plugin on Giuseppe Pastore's site](http://www.giuseppepastore.com/en/portfolio/wp-bots-analytics-plugin/ "SEO plugin")
== Installation ==

1. Upload `botsanalytics` directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Add the Web Property ID from Google Analytics (UA-XXXXXX-YY) to the settings (Admin > Settings > Bots Analytics)
1. Add the first number of your __utma cookie to the settings (Admin > Settings > Bots Analytics)
1. If you check 'I like this plugin!' chechbox  (Admin > Settings > Bots Analytics), your will credit the author with a link from your footer

== Frequently Asked Questions ==

= Do I have to insert the Javascript code of the new Google Analytics profile in my template? =

No, you don't, this is not required.

== Screenshots ==

1. How to retrieve the _utma cookie
2. Google Analytics Bots Dashboard

== Changelog ==

= 1.0 =
* Original release

= 2.0 =
* Fixed BingBot identification issues

== Upgrade Notice ==

= 1.0 =
* Original release

= 2.0 =
* Fixed BingBot identification issues

