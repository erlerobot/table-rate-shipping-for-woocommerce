=== WooCommerce Table Rate Shipping by Mangohour  ===
Contributors: mangohour
Tags: country, weight, cart total, price, woocommerce, table rate, shipping, calculator
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=sales@mangohour.com&item_name=Donation+for+Table+Rate+Shipping
Requires at least: 3.8
Tested up to: 3.9
Stable tag: trunk

Calculate shipping costs based on destination, weight and/or price. Supports unlimited country groups and rates.

== Description ==

This WooCommerce plugin is for anyone who needs to calculate shipping costs based on destination, weight and/or price. 

= Features =
* Unlimited shipping zones (country groups).
* Unlimited rates.
* Tier your shipping costs based on cart weight, or cart sub-total.
* Optional handling fees

This plugin requires WooCommerce 2.1 or above.

A premium version is also available with additional features such as multiple shipping methods (E.g 'Standard Shipping', 'Express Shipping'). [Click here to find out more](http://mangohour.com/plugins/woocommerce-table-rate-shipping).

I hope you will find this plugin useful! Please leave any feedback or questions in the support forum - I will do my best to help.

== Installation ==

1. Upload the `table-rate-shipping-for-woocommerce` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Activate the shipping method by going to WooCommerce > Settings > Shipping > Table Rate
4. Tick 'Enable this shipping method'
5. Configure your shipping rates and hit 'Save changes' when finished

After adding a shipping zone (country group), remember to hit 'Save changes' before proceeding to use it in a table rate.

== Frequently Asked Questions ==

= Will the plugin be updated? =

Yes I plan to keep updating the plugin to maintain compatibility.

= What currencies / weight units / languages are supported? =

The plugin is compatible with any WooCommerce currency/weight unit. Language translations will be added in a future update.

= How does the 'Everywhere Else' zone work? =

When a table rate uses 'Everywhere Else' as its zone, the table rate will only be applicable if the destination country does not appear in any defined shipping zone.

= I just want to calculate shipping costs based on destination, can I do this? =

Yes, just create a table rate using the zone, enter '0' for min and '*' for max. This will capture all carts destined for that shipping zone. '*' can be used in any max column to indicate there is no upper limit.

= What if multiple table rates are applicable for a cart?  =

The cheapest applicable rate will be chosen automatically for the customer.

== Screenshots ==

1. Settings screen
2. Cart example, using shown settings

== Changelog ==

= 1.0.2 =
* Fixed tax calculation bug.

= 1.0.1 =
* Improved readme.txt formatting.

= 1.0.0 =
* First release.