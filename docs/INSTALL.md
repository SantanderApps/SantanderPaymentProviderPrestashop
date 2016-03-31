# Install the module
## Before installation
* Make sure that you have an working Prestashop installation.

## Requirements
The following requirements must be fulfilled for this module to work.
* PHP version 5.3.0 or greater.
* PHP SoapClient ([http://php.net/manual/en/class.soapclient.php](http://php.net/manual/en/class.soapclient.php))
* Openssl
* cURL lib must be enabled for PHP ([http://php.net/manual/en/book.curl.php](http://php.net/manual/en/book.curl.php))
* libxml [http://php.net/manual/en/book.libxml.php](http://php.net/manual/en/book.libxml.php)

## Installation
### Install through Prestashop Control Panel
* Download the module from Prestashop's module directory using the module manager inside your Prestashop control panel.

### Manual installation
* Download the zip file from the GitHub repo and extract it on you local computer. In the folder of the current version is the zip file for the actual module. This is the one you upload to you Prestashop.
* Go to Prestashop control panel > Modules and Services.
* Click on "Add a new module".
* Upload the module in the "Module file" field.
* Browse for the zip file and select it and then click "Upload this module". The zip file is located in the folder of the current version and is named santandereasycontract.zip.
* When the module is uploaded it will appear in the module list on the page and it is named "Santander Consumer Bank - Monthly instalment".
* Click "install" on the module in the list.
* When the module is installed a page to configure the module is displayed for you.

## Configuration parameters
* **New order status:** Select the order status that the order will get when the order is placed.
* **Store ID:** Type the store ID that have been provided for you by Santander. This field will be automatically filled out when the module environment is set to "sandbox (test environment)".
* **Username:** Type the username that have been provided for you by Santander. This field will be automatically filled out when the module environment is set to "sandbox (test environment)".
* **Password:** Type the password that have been provided for you by Santander. This field will be automatically filled out when the module environment is set to "sandbox (test environment)".
* **Merchant ID:** (optional in sandbox/test environment) Type the merchant ID that have been provided for you by your payment service provider. See list below for supported payment service providers.
* **Set Module Environment:** Select which environment you want to run the module. Sandbox (test environment) is used for evaluating the module.
* **Support logs:** Check this if you want Santander to get access to log files that the module will create when used.

## Supported payment service providers
Santander supports the following payment service providers:
* Dibs
* DebiTech o Nets
* Payex
* Samport
