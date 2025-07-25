=== YITH WooCommerce Compare ===

Contributors: yithemes
Tags: yith, woocommerce compare, compare products, product compare, product comparison
Requires at least: 6.6
Tested up to: 6.8
Stable tag: 3.2.0
Requires PHP: 7.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

YITH WooCommerce Compare allows you to compare more products of your shop in one complete table.
WooCommerce Compatible up to 10.0

== Description ==

YITH WooCommerce Compare plugin is an extension of WooCommerce plugin that allow your users to compare some products of your shop.
All products are saved in one complete table where the user can see the difference between the products. Each product features can be
set with the woocommerce attributes in the product configuration.
You can also add a simple widget with the list of products the users have added, where you can manage them.
Also you can simply customize the compare table with your style, by editing the specific template.

Full documentation is available [here](https://docs.yithemes.com/yith-woocommerce-compare/).

This plugin is 100% compatible with [WPML](https://wpml.org/)


== Installation ==

**Important**: First of all, you have to download and activate [WooCommerce](https://wordpress.org/plugins/woocommerce) plugin, because without it YITH WooCommerce Compare cannot work.

1. Unzip the downloaded zip file.
2. Upload the plugin folder into the `wp-content/plugins/` directory of your WordPress site.
3. Activate `YITH WooCommerce Compare` from Plugins page

= Configuration =

1. Add the features in each product by setting the attributes in product configuration;
2. Configure the options in YIT Plugin -> Compare;
3. The user of your shop will click in the "Compare" button located in the single product page;
4. Will be open a popup with the compare table inside.

You can also add the widget with the product list of compare table, in Appearance -> Widgets and adding the widget "YITH WooCommerce Compare Widget".

== Frequently Asked Questions ==

= Can I customize the compare table? =
Yes, you can copy the template from the plugin folder and paste it inside the folder "woocommerce" of your theme folder.

= Can I select what fields show inside the compare table? =
Yes, you can choose what fields to show in the compare table. You can do it in YITH -> Compare.

= Can I order the fields in the compare table? =
Yes, you can sort the fields in the compare table. You can do it in YITH -> Compare.

= What are the main changes in plugin translation? =
Recently YITH WooCommerce Compare has been selected to be included in the "translate.wordpress.org" translate programme.
In order to import correctly the plugin strings in the new system, we had to change the text domain form 'yit' to 'yith-woocommerce-compare'.
Once the plugin will be imported in the translate.wordpress.org system, the translations of other languages will be downloaded directly from WordPress, without using any .po and .mo files. Moreover, users will be able to participate in a more direct way to plugin translations, suggesting texts in their languages in the dedicated tab on translate.wordpress.org.
During this transition step, .po and .mo files will be used as always, but in order to be recognized by WordPress, they will need to have a new nomenclature, renaming them in:
yith-woocommerce-compare-<WORDPRESS LOCALE>.po
yith-woocommerce-compare-<WORDPRESS LOCALE >.mo

= How can I report security bugs? =

You can report security bugs through the Patchstack Vulnerability Disclosure Program. The Patchstack team help validate, triage and handle any security vulnerabilities. [Report a security vulnerability.](https://patchstack.com/database/vdp/yith-woocommerce-compare)

== Screenshots ==

1. The popup with compare table.
2. The button compare.
3. The settings of plugin

== Changelog ==

= 3.2.0 = Released on 07 July 2025

* New: support for WooCommerce 10.0
* Update: YITH plugin framework

= 3.1.0 = Released on 27 May 2025

* New: support for WooCommerce 9.9
* Update: YITH plugin framework

= 3.0.1 = Released on 14 May 2025

- Tweak: make sure to enqueue plugin script when rendering widgets
- Fix: re-introduced YITH_WooCompare_Frontend::view_table_url
- Fix: removed owl assets where not needed
- Fix: warning undefined property YITH_WooCompare_Table::$page_template

= 3.0.0 = Released on 12 May 2025

* New: support for WordPress 6.8
* New: plugin look & feel
* New: layout for the compare button (checkbox)
* New: preview bar for items in comparison
* New: added compare button to WooCommerce grid blocks
* Tweak: major refactoring of plugin's code
* Update: YITH plugin framework
* Dev: added yith_woocompare_button_classes filter
* Dev: added yith_woocompare_should_show_preview_bar filter
* Dev: added yith_woocompare_products_list filter
* Dev: added yith_woocompare_cookie_value filter

= 2.48.0 = Released on 20 March 2025

* New: support for WooCommerce 9.8
* Update: YITH plugin framework

= 2.47.0 = Released on 13 February 2025

* New: support for WooCommerce 9.7
* Update: YITH plugin framework

= 2.46.0 = Released on 22 January 2025

* New: support for WooCommerce 9.6
* Update: YITH plugin framework

= 2.45.0 = Released on 12 December 2024

* New: support for WooCommerce 9.5
* Update: YITH plugin framework

= 2.44.0 = Released on 11 November 2024

* New: support for WordPress 6.7
* New: support for WooCommerce 9.4
* Update: YITH plugin framework

= 2.43.0 = Released on 16 September 2024

* New: support for WooCommerce 9.3
* Update: YITH plugin framework

= 2.42.0 = Released on 20 August 2024

* New: support for WooCommerce 9.2
* Update: YITH plugin framework

= 2.41.0 = Released on 18 July 2024

* New: support for WordPress 6.6
* New: support for WooCommerce 9.1
* Update: YITH plugin framework

= 2.40.0 = Released on 27 June 2024

* New: support for WooCommerce 9.0
* Update: YITH plugin framework

= 2.39.0 = Released on 23 May 2024

* New: support for WooCommerce 8.9
* Update: YITH plugin framework

= 2.38.0 = Released on 15 April 2024

* New: support for WooCommerce 8.8
* Update: YITH plugin framework
* Tweak: added nonces to ajax calls

= 2.37.0 = Released on 20 March 2024

* New: support for WordPress 6.5
* New: support for WooCommerce 8.7
* Update: YITH plugin framework
* Dev: filter yith_woocompare_redirect_status

= 2.36.0 = Released on 22 February 2024

* New: support for WooCommerce 8.6
* Update: YITH plugin framework

= 2.35.0 = Released on 18 January 2024

* New: support for WooCommerce 8.5
* Update: YITH plugin framework

= 2.34.0 = Released on 14 December 2023

* New: support for WooCommerce 8.4
* Update: YITH plugin framework

= 2.33.0 = Released on 19 November 2023

* New: support for WooCommerce 8.3
* New: support for WordPress 6.4
* Update: YITH plugin framework

= 2.32.0 = Released on 09 October 2023

* New: support for WooCommerce 8.2
* Update: YITH plugin framework

= 2.31.0 = Released on 12 September 2023

* New: support for WooCommerce 8.1
* Update: YITH plugin framework

= 2.30.1 = Released on 25 August 2023

* Fix: fatal error "Call to undefined function yith_plugin_fw_wc_is_using_block_template_in_product_catalogue()"

= 2.30.0 = Released on 25 August 2023

* New: support for WordPress 6.3
* Update: YITH plugin framework
* Dev: load compare button on plugins_loaded hook to prevent issues

= 2.29.1 = Released on 03 August 2023

* Fix: missing yith_plugin_fw_wc_is_using_block_template_in_single_product function

= 2.29.0 = Released on 03 August 2023

* New: support for WooCommerce 8.0
* New: support for WooCommerce block templates
* Update: YITH plugin framework

= 2.28.0 = Released on 19 July 2023

* New: support for WooCommerce 7.9
* Update: YITH plugin framework

= 2.27.0 = Released on 06 June 2023

* New: support for WooCommerce 7.8
* Update: YITH plugin framework

= 2.26.0 = Released on 09 May 2023

* New: support for WooCommerce 7.7
* New: support for WooCommerce HPOS feature
* Update: YITH plugin framework

= 2.25.0 = Released on 11 April 2023

* New: support for WooCommerce 7.6
* Update: YITH plugin framework

= 2.24.1 = Released on 23 March 2023

* Update: YITH plugin framework

= 2.24.0 = Released on 20 March 2023

* New: support for WooCommerce 7.5
* New: support for WordPress 6.2
* Update: YITH plugin framework

= 2.23.0 = Released on 14 February 2023

* New: support for WooCommerce 7.4
* Update: YITH plugin framework

= 2.22.0 = Released on 29 December 2022

* New: support for WooCommerce 7.3
* Update: YITH plugin framework

= 2.21.0 = Released on 13 December 2022

* New: support for WooCommerce 7.2
* Update: YITH plugin framework

= 2.20.1 = Released on 14 November 2022

* Update: YITH plugin framework
* Fix: patched security vulnerability

= 2.20.0 = Released on 27 October 2022

* New: support for WooCommerce 7.1
* New: support for WordPress 6.1
* Update: YITH plugin framework

= 2.19.0 = Released on 07 October 2022

* New: support for WooCommerce 7.0
* Update: YITH plugin framework

= 2.18.0 = Released on 31 August 2022

* New: support for WooCommerce 6.9
* Update: YITH plugin framework

= 2.17.0 = Released on 29 July 2022

* New: support for WooCommerce 6.8
* Update: YITH plugin framework

= 2.16.0 = Released on 14 July 2022

* New: support for WooCommerce 6.7
* Update: YITH plugin framework

= 2.15.0 = Released on 23 June 2022

* New: support for WooCommerce 6.6
* Update: YITH plugin framework

= 2.14.0 = Released on 17 May 2022

* New: support for WooCommerce 6.5
* New: support for WordPress 6.0
* Update: YITH plugin framework

= 2.13.0 = Released on 11 April 2022

* New: support for WooCommerce 6.4
* Update: YITH plugin framework

= 2.12.0 = Released on 09 March 2022

* New: support for WooCommerce 6.3
* Update: YITH plugin framework

= 2.11.0 = Released on 15 February 2022

* New: support for WooCommerce 6.2
* Update: YITH plugin framework

= 2.10.0 = Released on 17 January 2022

* New: support for WooCommerce 6.1
* New: support for WordPress 5.9
* Update: YITH plugin framework

= 2.9.0 = Released on 20 December 2021

* New: support for WooCommerce 6.0
* Update: YITH plugin framework

= 2.8.0 = Released on 11 November 2021

* New: support for WooCommerce 5.9
* Update: YITH plugin framework

= 2.7.0 = Released on 15 October 2021

* New: support for WooCommerce 5.8
* Update: YITH plugin framework

= 2.6.1 = Released on 27 September 2021

* Update: YITH plugin framework
* Fix: debug info feature removed for all logged in users

= 2.6.0 = Released on 09 September 2021

* New: support for WooCommerce 5.7
* Update: YITH plugin framework
* Fix: compare button preview on Elementor editor

= 2.5.4.1 = Released on 24 August 2021

* Fix: fatal error "Call to undefined method YITH_Woocompare_Admin::list_products_html()"
* Update: YITH plugin framework

= 2.5.4 = Released on 13 August 2021

* New: support for WooCommerce 5.6
* Update: YITH plugin framework

= 2.5.3 = Released on 14 July 2021

* New: support for WooCommerce 5.5
* New: support for WordPress 5.8
* Update: YITH plugin framework


= 2.5.2 = Released on 01 June 2021

* New: support for WooCommerce 5.4
* Update: YITH plugin framework

= 2.5.1 = Released on 06 May 2021

* New: support for WooCommerce 5.3
* Update: YITH plugin framework

= 2.5.0 = Released on 15 April 2021

* New: support for WooCommerce 5.2
* Update: YITH plugin framework
* Update: DataTables script to 1.10.24
* Update: FixedColumns script to 3.3.2

= 2.4.7 = Released on 01 April 2021

* Fix: 'clear all' button on compare widget

= 2.4.6 = Released on 04 March 2021

* New: support for WordPress 5.7
* New: support for WooCommerce 5.1
* Update: YITH plugin framework

= 2.4.5 = Released on 04 February 2021

* New: support for WooCommerce 5.0
* Update: YITH plugin framework

= 2.4.4 = Released on 12 January 2021

* New: Support for WooCommerce 4.9
* Update: Plugin framework

= 2.4.3 = Released on 09 December 2020

* New: Support for WooCommerce 4.8
* Update: Plugin framework

= 2.4.2 = Released on 02 November 2020

* New: Support for WordPress 5.6
* New: Support for WooCommerce 4.7
* Update: Plugin framework

= 2.4.1 = Released on 13 October 2020

* New: Support for WooCommerce 4.6.x
* Update: Plugin framework

= 2.4.0 = Released on 18 September 2020

* New: Support for WooCommerce 4.5.x
* Update: Plugin framework
* Tweak: Improved plugin responsive style

= 2.3.23 = Released on 19 August 2020

* New: Support for WooCommerce 4.4
* New: Support for WordPress 5.5
* Update: Plugin framework

= 2.3.22 = Released on 03 June 2020

* New: Support for WooCommerce 4.2
* Update: Plugin framework

= 2.3.21 = Released on 28 April 2020

* New: Support for WooCommerce 4.1
* Update: Plugin framework

= 2.3.20 = Released on 17 March 2020

* Fix: Use of undefined constant product_id

= 2.3.19 = Released on 10 March 2020

* New: Support for WooCommerce 4.0
* New: Support for WordPress 5.4
* Update: Plugin framework


= 2.3.18 = Released on 21 December 2019

* New: Support for WooCommerce 3.9
* New: Support for WordPress 5.3.2
* Update: Plugin framework

= 2.3.17 = Released on 29 November 2019

* Update: Plugin framework

= 2.3.16 = Released on 05 November 2019

* Update: Plugin framework

= 2.3.15 = Released on 30 October 2019

* Update: Plugin framework

= 2.3.14 = Released on 25 October 2019

* New: Support for WooCommerce 3.8
* New: Support for WordPress 5.3
* Update: Plugin framework

= 2.3.13 = Released on 08 August 2019

* New: Support to WooCommerce 3.7.0
* Update: Plugin Core

= 2.3.12 = Released on 12 June 2019

* Update: Plugin Core

= 2.3.11 = Released on 11 June 2019

* New: Support to WooCommerce 3.6.4
* New: Support to WordPress 5.2.1
* Update: Plugin Core
* Fix: Missed loader when adding products to the compare

= 2.3.10 = Released on 23 April 2019

* New: Support to WooCommerce 3.6.1
* Update: Plugin Core

= 2.3.9 = Released on 09 April 2019

* New: Support to WooCommerce 3.6.0 RC1
* Update: Plugin Core

= 2.3.8 = Released on 30 January 2019

* New: Support to WooCommerce 3.5.4
* Update: Plugin Core
* Fix: Sync AJAX request to prevent product missing

= 2.3.7 = Released on 05 December 2018

* New: Support to WooCommerce 3.5.2
* New: Support to WordPress 5.0.0
* Update: Plugin Core

= 2.3.6 = Released on 28 November 2018

* Update: Plugin Core
* Update: Language files
* Fix: Missing strings in pot and po files

= 2.3.5 = Released on 23 October 2018

* New: Support to WooCommerce 3.5.0
* Update: Plugin Core
* Fix: Product placeholder image and image size

= 2.3.4 = Released on 01 October 2018

* New: Support to WooCommerce 3.5.0 RC1
* Update: Plugin Core

= 2.3.3 = Released on 20 September 2018

* Fix: Compatibility issue with WPML and RTL languages

= 2.3.2 = Released on 10 September 2018

* New: Support to WooCommerce 3.4.5
* New: Support to WordPress 4.9.8
* Update: Plugin Core
* Update: All external scripts to latest available version
* Update: Compare table template (compare.php) to version 2.3.2
* Update: Compare table style
* Fix: Check product status before add it to compare list

= 2.3.1 = Released on 5 June 2018

* New: Support to WooCommerce 3.4.1
* New: Support to WordPress 4.9.6
* Update: Plugin Core
* Fix: WPML table fields translation

= 2.3.0 = Released on 2 February 2018

* New: Support to WooCommerce 3.3.0
* New: Support to WordPress 4.9.2
* Update: Plugin Core

= 2.2.3 = Released on 21 December 2017

* New: Support to WooCommerce 3.2.6
* New: Support to WordPress 4.9.1
* New: Product SKU field in compare table
* Update: Plugin Core
* Update: Language Files
* Dev: New filter yith_woocompare_standard_fields_array to filter standard compare fields

= 2.2.2 = Released on 24 October 2017

* New: Support to WooCommerce 3.2.1
* New: Support to WordPress 4.8.2
* Update: Plugin Core
* Update: Language Files

= 2.2.1 = Released on 05 July 2017

* New: Support to WooCommerce 3.1
* New: Support to WordPress 4.8
* New: Russian Translation
* New: Slovenian Translation
* Update: Plugin Core
* Update: Language Files
* Fix: WPML and Add to cart action from popup

= 2.2.0 = Released on 29 March 2017

* New: Support to WooCommerce 3.0.0 RC2
* New: Support to WordPress 4.7.3
* Update: Plugin Core
* Update: Language Files

= 2.1.0 = Released on 19 October 2016

* New: Support to WooCommerce 2.6.4
* New: Support to WordPress 4.6
* New: Auto remove from compare list for products that are private or were cancelled
* New: Add as default fields Weight and Dimensions
* Update: Plugin Core
* Update: Language Files
* Fix: Uncaught ReferenceError "redirect_to_cart is not defined" error on "add to cart" action
* Fix: Compatibility issue with NextGen Gallery plugin

= 2.0.9 = Released on 13 June 2016

* New: Support to WooCommerce 2.6 RC1
* Update: Plugin Core

= 2.0.8 = Released on 19 April 2016

* New: Compatibility with WordPress 4.5
* Update: Plugin Core.
* Fix: Fatal error call to undefined method WC_AJAX::get_endpoint() for WooCommerce version older then 2.4

= 2.0.7 = Released on 01 April 2016

* Update: Plugin template compare.php
* Update: Plugin Core
* Update: Language file
* Fix: Product status now updates automatically when the product is removed from the compare widget
* Fix: Redirect correctly to cart page after "Add to cart" is clicked if "Redirect to the cart page after successful addition" option is enabled
* Fix: Redirect correctly to product page after "Add to cart" is clicked when "Enable AJAX add to cart buttons on archives" option is disabled

= 2.0.6 = Released on 11 January 2016

* New: Compatibility with WooCommerce 2.5 RC
* Update: Change ajax call fron admin-ajax to wc-ajax
* Update: Plugin template compare.php
* Update: Plugin Core

= 2.0.5 = Released on 30 October 2015

* Update: Plugin Core
* Fix: After you remove product from compare, you can re-add it without reload page

= 2.0.4 = Released on 22 September 2015

* Update: Changed Text Domain from 'yith-wcmp' to 'yith-woocommerce-compare'
* Update: Plugin Core Framework
* Fix: JS error when loading compare window

= 2.0.3 = Released on 21 August 2015

* New: Compatibility with WooPress 4.3

= 2.0.2 = Released on 12 August 2015

* New: Compatibility with WooCommerce 2.4
* Update: Core plugin

= 2.0.1 = Released on 10 August 2015

* Update: Core plugin
* Fix: Compare table layout
* Fix: undefined function unblock() in main js

= 2.0.0 = Released on 15 July 2015

* New: New plugin core
* Update: Language files
* Removed: old default.po catalog language file
* Fix: Error in class yith-woocompare-fontend
* Fix: Lightbox doesn't close after click view cart
* Fix: minor bug fix

= 1.2.3 = Released on 13 February 2015

* New: Bulgarian Translation by Joanna Mikova
* New: Spanish Translation by Rodoslav Angelov and Mariano Rivas

= 1.2.2 = Released on 03 December 2014

* Fix: Shortcode compare

= 1.2.1 = Released on 17 September 2014

* New: Support to WC 2.2.3

= 1.2.0 = Released on 16 September 2014

* New: Support to WC 2.2.2
* Update: Compare Template
* Update: Plugin Core Framework
* Fix: Fields orders
* Tweek: WPML Support improved

= 1.1.4 = Released on 30 June 2014

* Update: Colorbox Library Version 1.5.10
* Fix: Horizontal scroll bar issue: show at the end of iframe

= 1.1.3 = Released on 05 June 2014

* New: RTL Support

= 1.1.2 = Released on 21 March 2014

* Fix: WPML Support on Compare Widget

= 1.1.1 = Released on 19 February 2014

* Fix: Add to cart Button on Compare page

= 1.1.0 = Released on 13 February 2014

* New: Support to WooCommerce 2.1.X
* New: French translation by Paumo

= 1.0.5 = Released on 14 October 2013

* New: Persian translation by Khalil Delavaran
* New: Compare table title option
* New: Compatibility with WPML plugin
* New: Brazilian Portuguese translation by hotelwww
* Fix: Responsive features
* Fix: Dequeued wrong JS scripts
* Update: Dutch translation by Frans Pronk

= 1.0.4 = Released on 04 September 2013

* New: complete Dutch translation. Thanks to Frans Pronk
* Fix: Sortable scripts included only in the plugin admin page
* Fix: products list in popup don't update after have added a product

= 1.0.3 = Released on 31 July 2013

* Minor bugs fixes

= 1.0.2 = Released on 20 July 2013

* Tweak: trigger in javascript file for add to compare event

= 1.0.1 = Released on 27 June 2013

* New: Link/Button text option in plugin options
* New: ability to add a link in the menu top open the popup
* Fix: bug with attributes added after installation
* Fix: bug with plugin activated but not working for multisites

= 1.0.0 = Released on 24 June 2013

* Initial release

== Suggestions ==

If you have suggestions about how to improve YITH WooCommerce Compare, you can [write us](mailto:plugins@yithemes.com "Your Inspiration Themes") so we can bundle them into YITH WooCommerce Compare.

== Translators ==

= Available Languages =
* English (Default)
* Italiano

If you can't find this plugin in your language and want to translate it, use the dedicated tool at [Translating WordPress](https://translate.wordpress.org/locale/it/default/wp-plugins/yith-woocommerce-compare "Translating WordPress").
Or, if you have created your own language pack, or have an update for an existing one, you can send it as an email attachment from our [Contacts page](http://yithemes.com/contact/ "Your Inspiration Themes") and we will bundle into YITH WooCommerce Compare.

== Documentation ==

Full documentation is available [here](https://docs.yithemes.com/yith-woocommerce-compare/).

== Upgrade notice ==

= 2.30.1 = Released on 25 August 2023

* Fix: fatal error "Call to undefined function yith_plugin_fw_wc_is_using_block_template_in_product_catalogue()"
