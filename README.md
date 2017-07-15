<h1>WooCommerce</h1>
<hr>
<h2>Getting Started with WooCommerce Theme Development</h2>
<ul>
    <li>
        <h3>Starter Theme Setup</h3>
        <p>Install WordPress, Woocommerce, impord WordPress plugin, Child Theme Configurator. After I import the dummy-data.xml in woocommerce plugin folder. If you have import issues, check ticket #24373 in Make WordPress Core or changeset 718670 for wordpress-importer. Create Twenty Seventeen Child theme and activate it.</p>
    </li>
    <li>
        <h3>Default WooCommerce Template Files</h3>
        <p>WooCommerce template files contain the markup and template structure for frontend and HTML emails of your store. Template files can be found within the /woocommerce/templates/ directory. To edit these files in an upgrade-safe way using overrides.</p>
    </li>
    <li>
        <h3>How to Override a Default Template File</h3>
        <p>To override the admin order notification, copy: <br>
        wp-content/plugins/woocommerce/templates/emails/admin-new-order.php to<br>
        wp-content/themes/yourtheme/woocommerce/emails/admin-new-order.php <br>
        But If your theme has a woocommerce.php file, you will be unable to override the woocommerce/archive-product.php. archive-product.php — displaying product archives, including the main shop page which is a post type archive. Copy plugins/woocommerce/archive-product.php to twentyseventeen-child/woocommerce/archive-product.php look after changing. Also look at cart/cart.php</p>
    </li>
</ul>

