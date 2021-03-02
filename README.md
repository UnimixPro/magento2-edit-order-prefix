# Magento 2 - Edit Order Prefix
Often the administrator needs to change the prefix to process orders.  This module helps you to edit the prefix for orders/shipments/invoices/credit memo/rma for each store/web sites. This is very convenient when you have several stores, you can easily search for orders, or import them into your crm.

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/Unimix`
 - Enable the module by running `php bin/magento module:enable Unimix_EditOrderPrefix`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`
 
## Features
- You can specify any prefix for orders/shipments/invoices/credit memo/rma.
- This will help you easily search for the right orders
- Admin can choose any kind of custom prefix including alphabetical, numeric, etc.
- You can use it for different stores/sites.
- Easy installation

## Support
If you encounter any problems or bugs, please open an issue on [GitHub](https://github.com/UnimixPro/magento2-edit-order-prefix/issues/new).



Magento 2 Extensions
---
- [All Our Modules](https://unimix.pro/magento/our-modules)

 
 © Unimix Pro LLC. | [https://unimix.pro/](https://unimix.pro/)



