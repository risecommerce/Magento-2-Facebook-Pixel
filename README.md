# Risecommerce Magento 2 Facebook Pixel Extension

This [Magento 2 Facebook Pixel](https://risecommerce.com/https-risecommerce-com-magento2-facebook-pixel-html.html) extension allows to add Facebook Pixel Code in your store to track your visitors� events and the effectiveness of your Facebook ads.

For more details about this extension, visit the [Magento 2 Facebook Pixel](https://risecommerce.com/https-risecommerce-com-magento2-facebook-pixel-html.html).

If you're looking to enhance your Magento store further, consider hiring a [dedicated Magento developer](https://risecommerce.com/hire-dedicated-magento-developer.html).

For support or inquiries, please visit our [contact page](https://risecommerce.com/contact).

## Support: 
version - 2.3.x, 2.4.x

## How to install Extension

Method I)

1. Download the archive file.
2. Unzip the files
3. Create a folder [Magento_Root]/app/code/Risecommerce/FacebookPixel
4. Drop/move the unzipped files to directory '[Magento_Root]/app/code/Risecommerce/FacebookPixel'

Method II)

Using Composer

composer require risecommerce/magento-2-facebook-pixel-extension:1.0.1

### Enable Extension:
- php bin/magento module:enable Risecommerce_FacebookPixel
- php bin/magento setup:upgrade
- php bin/magento setup:di:compile
- php bin/magento setup:static-content:deploy
- php bin/magento cache:flush

### Disable Extension:
- php bin/magento module:disable Risecommerce_FacebookPixel
- php bin/magento setup:upgrade
- php bin/magento setup:di:compile
- php bin/magento setup:static-content:deploy
- php bin/magento cache:flush
