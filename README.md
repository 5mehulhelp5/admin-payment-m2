# Magento 2 Admin Payment Method Extension

Enhance your store's order management capabilities with our Magento 2 Admin Payment Method Extension. This extension allows store administrators to assign or change payment methods for orders directly from the admin panel, providing greater flexibility in handling special orders, offline payments, and customer-specific payment arrangements.

## Key Features:

- **Admin-Side Payment Assignment:**
Allow admin users to select and assign payment methods to orders directly from the Magento 2 Admin Panel.
- **Custom Payment Methods:**
Add and configure custom offline or manual payment methods exclusively available for admin use.
- **Order Edit Support:**
Change or update the payment method on existing orders without cancelling and recreating them.
- **Payment Method Restriction:**
Restrict specific payment methods to admin-only use, preventing them from appearing on the frontend for customers.
- **Detailed Payment Logs:**
Maintain a complete log of all payment method assignments and changes made by admin users.
- **Filter and Search:**
Easily search and filter orders by admin-assigned payment methods for efficient order management.
- **Email Notifications:**
Automatically notify customers when an admin updates the payment method on their order.

## Benefits:

- **Greater Order Flexibility:**
Handle special orders, corporate clients, and offline payments with ease using admin-assigned payment methods.
- **Streamlined Operations:**
Reduce the need for order cancellations by allowing payment method changes directly on existing orders.
- **Enhanced Admin Control:**
Give your admin team the tools they need to manage complex payment scenarios without developer assistance.
- **Improved Customer Service:**
Quickly resolve payment-related issues for customers by updating payment methods at the admin level.

## Compatibility:
This extension is compatible with Magento 2.x versions, ensuring seamless integration with your existing store setup.

## Installation:
**Install via composer (recommend)** -

Easy installation process with step-by-step instructions provided for hassle-free setup.
~~~~~~~~~~~~~~~~~~~~~
composer require mavenbird/module-adminpaymentmethod
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento cache:flush
~~~~~~~~~~~~~~~~~~~~~

## Upgrade/Update Module:
Run the following command in Magento 2 root folder for easy update -
~~~~~~~~~~~~~~~~~~~~~
composer update mavenbird/module-adminpaymentmethod
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento cache:flush
~~~~~~~~~~~~~~~~~~~~~

## Configuration Options:
Tailor the admin payment method settings to your store's requirements with customizable options for available payment methods, restriction rules, and notification preferences. Access the configuration settings from the Magento 2 Admin Panel under Stores > Configuration > Admin Payment Method.


## Support:
Dedicated support team available to assist with installation, customization, and any other queries or concerns.
*[support@mavenbird.com](mailto:support@mavenbird.com)*

## Get Started:
Unlock greater payment flexibility and admin control with our Magento 2 Admin Payment Method Extension. Start managing your store's payment methods more efficiently today!

**Thank you!**
