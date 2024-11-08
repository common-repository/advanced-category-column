=== Advanced Category Column ===
Contributors: tepelstreel
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=BC9QUKBEZFZFY
Tags: column, sidebar, widget, category, newspaper, image, multi widget
Requires at least: 2.9
Tested up to: 4.5
Stable tag: 3.5

The Advanced Category Column is a very customizable multi-widget for your sidebar.

== Description ==

The Advanced Category Column is mainly designed to give your blog a bit more of a newspaper behavior. E.g. The plugin shows the latest posts from all categories with an offset of three posts on your homepage.

If there is a post thumbnail, it will be displayed above the headline of the post. No further text will appear. If there is no thumbnail, only the headline and the excerpt of the post will be shown. When the plugin can detect neither the thumbnail nor the excerpt of a post, it will display just the first couple of sentences (or words) of a post.

So far that is the same as my Category Column Plugin does also. Not every theme has the possibility to hide certain sidebars on different pages. That's where the advanced of our plugin comes in. In the ACC you can determine, where exactly the widget is showing and in the settings you can customize the links of your widget(s).

== Installation ==

1. Upload the `advanced-category-column` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place and customize your widgets
4. Customize your links in the settings

== Frequently Asked Questions ==

= The Widget doesn't show on my site =

Look at the source code of your site. If it says at one point,

'Advanced Category Column Widget is not setup for this view.'

you can change the visibility of the widget in the widget's settings according to your choices.

= I styled the widget container myself and it looks bad. What do I do? =

The styling of the widget requires some knowledge of css. If you are not familiar with that, try adding

`padding: 10px;
margin-bottom: 10px;`
 
to the style section.

= My widget should have rounded corners, how do I do that? =

Add something like

`-webkit-border-top-left-radius: 5px;
-webkit-border-top-right-radius: 5px;
-moz-border-radius-topleft: 5px;
-moz-border-radius-topright: 5px;
border-top-left-radius: 5px;
border-top-right-radius: 5px;`
 
to the widget style. This is not supported by all browsers yet, but should work in almost all of them.

= My widget should have a shadow, how do I do that? =

Add something like

`-moz-box-shadow: 10px 10px 5px #888888;
-webkit-box-shadow: 10px 10px 5px #888888;
box-shadow: 10px 10px 5px #888888;`
 
to the widget style to get a nice shadow down right of the container. This is not supported by all browsers yet, but should work in almost all of them.

= I styled the links of the widget differently, but the changes don't show, what now? =

Most of the time you will have to use the styles like that:

'font-weight: bold !important;
color: #0000dd !important;'

Since some other stylesheets can have a higher priority, you will have to make your styles more important in the hierarchy.

== Screenshots ==

1. The plugin's work on our homepage
2. The widget's settings section
3. The plugin's settings section

== Changelog ==

= 3.5 =

* Framework adjusted
* WP 4.5 ready

= 3.4.2 =

* WP 4.3 ready

= 3.4.1 =

* WP 4.2 ready

= 3.4 =

* Framework adjusted

= 3.3 =

* Framework adjusted
* Made ready for Custom Login Page
* Made rady for WP 4.1

= 3.2.2 =

* Mistake in image class fixed

= 3.2.1 =

* Interference with Wordpress Page Widgets eliminated

= 3.2 =

* DSS is now compressible

= 3.1 =

* All 'Divided by Zero' errors should be eliminated

= 3.0 =

* More foolproof

= 2.9 =

* Adjusted framework; better ability to get images

= 2.8.2 =

* Instead of styling each individual widget, you can style now the whole class

= 2.8.1 =

* minor bugfix and image border added

= 2.8 =

* more responsive; Spanish translation added thanks to [Andrew Kurtis](http://www.webhostinghub.com/)

= 2.7.5 =

* Inner beauty not well working; bug fixed

= 2.7.4 =

* No bugfix, but inner beauty added :)

= 2.7.3 =

* more accurate and easy thumbnails in the widget
* added the possibility to get unfiltered excerpt to avoid possible interferences with other plugins

= 2.7.2 =

* bug with title heading fixed

= 2.7.1 =

* bug fixed in the framework

= 2.7 =

* small changes in the framework
* possibility to adjust the title heading

= 2.6 =

* added a possible post byline to the widget
* some code streamlined

= 2.5.1 =

* small bugfix

= 2.5 =

* Great reduction of the payload by adding a cache to the plugin

= 2.4 =

* Adjusting the classes to be more like allrounders

= 2.3 =

* Complete overhaul of the code; it should be cleaner, some typos should have disappeared

= 2.2 =

* Added ability to get thumbnails also if using galleries
* Uses now dss instead of writing a new css file, when saving the styles
* More accurate auto excerpt

= 2.1 =

* Bugfix

= 2.0 =

* Minor bugfixes, check all function added

= 1.5 =

* The text-areas are now resizable and the input fields got smaller

= 1.2 =

* Bug with empty stylesheet on update fixed

= 1.1 =

* Bugfix concerning title slugs; settings accessible from plugin page now

= 1.0 =

* Stable version with Dutch and German language files

= 0.5 =

* Public Beta and initial release

= 0.3 =

* Open Beta

== Upgrade Notice ==

= 1.0 =

Stable and clean version

= 1.1 =

Bugfix concerning title slugs; settings accessible from plugin page now

= 1.2 =

Bug with empty stylesheet on update fixed

= 1.5 =

The text-areas are now resizable and the input fields got smaller

= 2.0 =

Minor bugfixes, check all function added

= 2.1 =

Bugfix

= 2.2 =

Added ability to get thumbnails also if using galleries
Uses now dss instead of writing a new css file, when saving the styles
More accurate auto excerpt

= 2.3 =

Complete overhaul of the code; it should be cleaner, some typos should have disappeared

= 2.4 =

Adjusting the classes to be more like allrounders

= 2.5 =

Great reduction of the payload by adding a cache to the plugin

= 2.5.1 =

small bugfix

= 2.6 =

added a possible post byline to the widget

= 2.7 = 

possibility to change post heading

= 2.7.1 =

bug fixed in framework

= 2.7.2 =

bug with title heading fixed

= 2.7.3 =

more accurate and easy thumbnails in the widget; added the possibility to get unfiltered excerpt to avoid possible interferences with other plugins

= 2.7.4 =

No bugfix, but inner beauty added :)

= 2.7.5 =

Inner beauty not well working; bug fixed

= 2.8 =

more responsive; Spanish translation added

= 2.8.1 =

minor bugfix; image border added

= 2.8.2 =

Instead of styling each individual widget, you can style now the whole class

= 2.9 =

Adjusted framework; better ability to get images

= 3.0 =

More foolproof

= 3.1 =

All 'Divided by Zero' errors should be eliminated

= 3.2 =

DSS is now compressible

= 3.2.1 =

Interference with Wordpress Page Widgets eliminated

= 3.2.2 =

Mistake in image class fixed

= 3.3 =

Framework adjusted; made ready for Custom Login Page; made rady for WP 4.1

= 3.4 =

Framework adjusted

= 3.4.1 =

WP 4.2 ready

= 3.4.2 =

WP 4.3 ready

= 3.5 =

Framework adjusted; WP 4.5 ready