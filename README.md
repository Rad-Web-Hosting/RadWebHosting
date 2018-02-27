<p align="center"><a href="https://radwebhosting.com" target="_blank"><img width="350" src="https://avatars0.githubusercontent.com/u/16030710?s=460&v=4" alt="RAD WEB HOSTING"></a></p>

## About
This is a custom WHMCS module built for our resellers to enable remote Domain Registration and management of RAD WEB HOSTING domains.

## Installation
1. Download the module via the following [link](https://github.com/Rad-Web-Hosting/RadWebHosting/releases/latest)
1. Copy the `RadWebHosting` directory into the respective WHMCS directory in your WHMCS setup: `/whmcs/modules/registrars/`
2. In WHMCS Admin area, navigate to Setup -> Products/Services -> Domain Registrars and activate the `RadWebHosting` registrar
3. Enter your API username and API secret. These can be obtained via your [Hosting Dashboard](https://radwebhosting.com/client_area/clientarea.php).
4. Choose to pay via credit card. You must have one on file. This will ensure domains are registered/renewed when your WHMCS requests. If you do not want to use a credit card, you must have a credit balance on your account with RAD WEB HOSTING.
5. Add the following code to /includes/additionaldomainfields.php if using WHMCS v6 or add to /resources/domains/additionalfields.php if using WHMCS v7:
```
/********************************************* RadWebHosting Domain Additional Fields ********************************************/
if(!defined('DS'))
    define('DS',DIRECTORY_SEPARATOR);
$filename = ROOTDIR.DS.'modules'.DS.'registrars'.DS.'RadWebHosting'.DS.'RadWebHosting.php';
if(file_exists($filename)){
    require_once ($filename);
    $fields = RadWebHosting_GetDomainFields();
    if(is_array($fields))
        $additionaldomainfields = $fields;     
}
/********************************************* End RadWebHosting Domain Additional Fields *****************************************/
```

## Help
If you have any questions or problems please submit a [Domain Support Ticket](https://radwebhosting.com/client_area/client_area/submitticket.php?step=2&deptid=10).

## Bugs
If you discover any bugs or issues with this module, please notify our staff via the [24/7 Helpdesk](https://radwebhosting.com/client_area/submitticket.php).

## License
This project is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
