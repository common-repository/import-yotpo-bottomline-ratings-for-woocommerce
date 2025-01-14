=== Import Yotpo Bottomline Ratings for WooCommerce ===
Contributors: roymckenzie, mintunmedia
Tags: woocommerce, yotpo, ratings, api
Donate link: https://paypal.me/roypmckenzie/3
Requires at least: 4.9.4
Tested up to: 4.9.4
Requires PHP: 5.5.38
Stable tag: trunk
License: GNU General Public License v2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Import Yotpo Bottomline Ratings into your WooCommerce products meta.

== Description ==
Import Yotpo Bottomline Ratings for WooCommerce connects to the Yotpo API to import the average rating and the number of reviews as meta fields on your products. You can then use these meta fields to perform custom queries to determine most popular products, most reviewed products, etc.

Connects to the Yotpo API at regular intervals of your choosing or on-demand to update ratings.

== Installation ==
1. Upload "import-yotpo-bottomline-ratings-for-woocommerce.php" to the "/wp-content/plugins/" directory.
2. Activate the plugin through the "Plugins" menu in WordPress.
4. Add your Yotpo API Key and API Secret pair on the settings panel *WooCommerce->Import Yotpo Ratings*.

== Frequently Asked Questions ==
= What are the meta keys for the Yotpo product score and the Yotpo total reviews that are added to my products? =
The meta keys are `yotpo_product_score` and `yotpo_total_reviews`, respectively.

== Screenshots ==
1. Settings Page.
2. Custom fields populated with Yotpo ratings and review count.

== Changelog ==
= 0.1 =
* Initial release.