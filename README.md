# Mage2 Module Hgati CurrencyConverter (for Magento v2.4.6)

    ``composer require hgati/module-currencyapi-converter``

 - [Main Functionalities](#user-content-main-functionalities)
 - [Installation](#user-content-installation)
 - [Configuration](#user-content-configuration)
 - [Specifications](#user-content-specifications)
 - [Attributes](#user-content-attributes)


## Main Functionalities
This is magento 2 module which provides integration of free currency converter(currencyapi.net) API.

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/Hgati`
 - Enable the module by running `php bin/magento module:enable Hgati_CurrencyApiConverter`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require hgati/module-currencyapi-converter`
 - enable the module by running `php bin/magento module:enable Hgati_CurrencyApiConverter`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Configuration

 - API Key (currency/currencyapi/api_key)

 - Connection Timeout in Seconds (currency/currencyapi/timeout)


## Specifications




## Attributes



