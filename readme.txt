=== oxyXML generator ===
Contributors: Olivier PIERRE, Ludovic ANDRE
Requires at least: 2.5
Tested up to: 2.7.1
Stable tag: 0.2
Tags: xml, export, display

This plugin creates a XML file from your posts in order to display them on another website, using PHP or Flash.

== Description ==

This plugin creates a XML posts.xml file containing posts from your blog.
This xml file can then be used to display your posts on another website using PHP or Flash.
Based on Valentin Karailiev's karailievs-sitemap plugin

= Changes in version 0.2 =

- Using backend scripts from WP to fetch data from database (@Ludovic)
- Display debug error if occurs (@Ludovic)
- Redesigned admin panel to add more informations (@Olivier)
- User must now check boxes to choose the categories of posts to export, instead of providing an ID list (@Olivier)
- User can choose to export xxx posts per category or posts not older than yyy days (@Olivier)
- User can choose which items to export (date, url, category name, etc...) (@Olivier)

== Installation ==

1. Upload `oxyxml` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Create a file named posts.xml in your blog folder. The file must be writable for the web server.
1. Turn the plugin on via the Settings -> oxyXML screen
1. Open your xml file to test it (e.g. http://www.your_domain_name.com/posts.xml)

== Frequently Asked Questions ==

= How can I use the XML file to display posts on another website ? =

There is a PHP example on my blog here : http://www.oxeron.com/2009/02/20/oxyxml-01-wordpress-plugin

== Screenshots ==
None