# Introduction :

This magento 2 extension adds the ChromePhp class to magento.

[ChromePhp](https://github.com/ccampbell/chromephp) is a PHP library for the Chrome Logger Google Chrome extension.
This library allows you to log variables to the Chrome console.

# Installation:

1. git clone https://github.com/Eddcapone/ChromePhp.git
2. bin/magento module:enable Eddcapone_ChromePhp
3. bin/magento setup:upgrade
4. bin/magento setup:di:compile

# Usage:

Use class:

    use \Eddcapone\ChromePhp\Helper\ChromePhp;

Now you can access the static methods:

    ChromePhp::log('Hello console!');
    ChromePhp::log($_SERVER);
    ChromePhp::warn('something went wrong!');
