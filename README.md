# magento2-module-fedex-fix
Magento 2 Module for fixing Fedex Shipping method for UK

# Implementation
Magento hadn't updated their Fedex implementation since release - mainly only worked for US based fedex shipments and on a very old version of the API.

The module overrides Magento\Fedex\Model\Carrier with a modified/updated version.

# Features
Upgrade Fedex API from V10 - to the more current V31

Updates to the Carrier API requests/response handlers to work with the updated API version.

Add in Newer Carrier codes for Fedex Services UK/EU

Add in Convert Currency codes from Fedex's own made up ones to ISO codes so Magento can understand them at checkout.

# Notes
Module was created on Magento 2.4.3-p2 
Tested on 2.4.3-p2, 2.4.3-p3, 2.4.6-p1
