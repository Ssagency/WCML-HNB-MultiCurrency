=== HNB Multi Currency for WPML ===
Contributors: mariorendic
Tags: woocommerce, multilingual, wpml, exchange rates, currency, hnb, tečaj, tečajna lista, api
Donate link: https://simplesolutions.hr/plugins/hnb/
Requires at least: 4.6
Tested up to: 5.2
Requires PHP: 5.3
Stable tag: trunk

Adds additional exchange rates for WooCommerce Multilingual - HNB (Croatian National Bank) (via https://www.hnb.hr/hnb-api).


== Description ==

* Due to bug in WooCommerce Multilingual, plugin works only with WPML plugin versions:

WPML Multilingual CMS 4.3.0-b.6 >
WooCommerce Multilingual 4.7.0-b.6 >

This plugin extends the functionality of [WooCommerce Multilingual](https://wordpress.org/plugins/woocommerce-multilingual/) for automated exchange rates by adding additional exchange rates services:

* [HNB - Croatia National Bank](https://www.hnb.hr/core-functions/monetary-policy/exchange-rate-list/exchange-rate-list) - rates are obtained from free API and doesn't require API key.
* Plugin connects to HNB API to get middle rates.
* [API url] (https://www.hnb.hr/hnb-api)
* [API response] (http://api.hnb.hr/tecajn/v2)


= Why to use this plugin: =
* By Croatian Law all companies that use multi currency have to use official middle exchange rate from HNB (Croatia National Bank)

= Currencies can be converted from and to: =
* HRK - Croatian Kuna
* AUD - Australian Dollar
* CAD - Canadian Dollar
* CZK - Czech Koruna
* DKK - Danish Krone
* HUF - Hungarian Forint
* JPY - Japanese Yen
* NOK - Norwegian Krone
* SEK - Swedish Krona
* CHF - Swiss Franc
* GBP - Pound sterling
* USD - United States Dollar
* BAM - Bosnia-Herzegovina Convertible Mark
* EUR - Euro
* PLN - Poland złoty
* Please note other currencies aren't provided as HNB API doesn't support them.

= Requires following plugins =
* [WooCommerce](https://wordpress.org/plugins/woocommerce/)
* [WPML](https://wpml.org/)
* [WooCommerce Multilingual](https://wordpress.org/plugins/woocommerce-multilingual/)


== Installation ==

= 1. Install the plugin =

The latest versions are always available in the WordPress Repository, and you can choose one of your favorite ways to install it:

* automatically using [built-in plugin installer](https://codex.wordpress.org/Managing_Plugins#Automatic_Plugin_Installation) (recommended)
* manually by [uploading a zip archive](https://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation_by_FTP)
* manually by [FTP](https://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation_by_Uploading_a_Zip_Archive)

= 2. Complete the setup =

Select the newly added service in `WooCommerce -> WooCommerce Multilingual -> Multi curency`.

1. Enable `Enable automatic exchange rates`
1. Select the newly added service - HNB - in `Exchange rates source`.
1. Select update frequency - recommended is `daily`.
1. Save the settings (otherwise the rate will be changed by following step but you would need to refresh the page in order to see it).
1. Now you could click on `update manually now` button to update the rates for the first time.


== Frequently Asked Questions ==

= What about my data & privacy? =

The list of currencies used on your website is used to call to exchange rate service to get the exchange rate back. Your store's data will not be transmitted. All data (e.g., price conversion itself) is still handled by [WooCommerce Multilingual](https://wordpress.org/plugins/woocommerce-multilingual/).

= What about aditional functionality =

In next versions of plugin we plan to include functionality to display currency rate and value in original currency on checkout and in order mail.

== Credits ==

= Author: [Mario Rendić - Simple Solutions](https://www.simplesolutions.hr)  =

= Partners: [Maoio Agency](https://maoio.agency)  =

= Special thanks to:  =

= [Borko Livic - Media-X](https://media-x.hr)  =
= [Karolína Vyskočilová](https://kybernaut.cz)  =

== Screenshots ==

1. HNB Exchange rate service


== Upgrade Notice ==


== Changelog ==

= 1.0 (2019-09-02) =
* Initial release