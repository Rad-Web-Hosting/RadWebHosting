# Domains-Reseller-whmcs
Domains Reseller module for WHMCS to integrate API functionality for resellers directly into their WHMCS installations. Simplifies the automation of registering, transferring, and renewing domain name registrations. RAD WEB HOSTING account is required.

After account creation, users gain access to the Domain API by siging up for a Domain Reseller account.

<p align="center"><a href="https://radwebhosting.com" target="_blank"><img width="350" src="https://avatars0.githubusercontent.com/u/16030710?s=460&v=4" alt="RAD WEB HOSTING"></a></p>

## About
* This is a Domain Registrar module for WHMCS to integrate API functionality for Domains resellers, allowing them to remotely manage Rad Web Hosting domain names in remote WHMCS installation. This module also installs Client Area domain management functions for use by end-clients.
* Simplifies the automation of registering, transferring, and renewing domain names, and provides for complete remote control of all domain functions. 

## Prerequisites
Please read the following system requirements for WHMCS Domain Reseller module:
* Working WHMCS installation (v5.3+)
* RAD WEB HOSTING API key

Users can gain access to API key by signing up for a Domain Reseller account

## Installation
1. Download the module
2. Upload  to the WHMCS root directory (i.e. /home/user/whmcs ) and extract the files
3. In WHMCS Admin area, navigate to Setup -> Products/Services -> Domain Registrars and activate the `radwebhosting` registrar
4. Enter your API username and API secret. These can be obtained via your Hosting Dashboard.
5. Add funds to your account. API domain registrations/transfers/renewals are paid using your existing account balance. PayPal, Credit Cards, and over 40 cryptocurrencies can be used for funding. $20 is the minimum funds allowed per transaction.

## API Features
* DNS Modifications
* Email Forwarding
* Private Registrations 
* Modify Contacts
* Modify Registrar Lock/Unlock
* Get Domain Auth Code
* Domain/URL Forwarding
* DNS Management (A, AAAA, CNAME, MX, TXT)
* Domain suggestion, domain delete

* Register/Transfer/Renew Domain
* Release/Delete Domain
* Get/Modify Contact Details
* Get EPP Code
* Get/Modify Registrar Lock Status
* Get/Save DNS Records
* Get/Register/Modify/Delete Nameservers
* Get/Save Email Forwarding
* Modify ID Protection
* Check Domain And Transfer Synchronization
* Check Domain Availability
* Get Available TLDs
* Get Available Credits
* Get Version

For full documentation, please visit the Rad Web Hosting Domain API documentation on the website.

## Help
If you have any questions or problems please submit a [Domain Support Ticket](https://radwebhosting.com/client_area/submitticket.php?step=2&deptid=10).

## Bugs
If you discover any bugs or issues with this module, please notify our staff via the [24/7 Helpdesk](https://radwebhosting.com/client_area/submitticket.php).

## License
This project is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
