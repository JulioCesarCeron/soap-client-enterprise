Javascript SOAP Client
======================

Forked from http://javascriptsoapclient.codeplex.com/


Improvements
------------

* Parsing exceptions fixed
* Arrays as parameters correctly sets the length attribute in the type definiton
* Arrays are also parsed out of responses if they aren't listed in the wsdl
* Understands responses from php webservice (for example Magento)
* IE9 compatible

Tested
------

* Magento Webservice (PHP online store system)

Please leave me a note if you have tested other webservices or found bugs.
New versions available at: https://github.com/gtathub/js-soap-client

* Original work by Matteo Casati (based on v2.4 from 2007-12-21)
* Improved by Gordon Tschirner ([gtathub](https://github.com/gtathub))
* Licensed under GPLv2: https://github.com/gtathub/js-soap-client.git

Changes
-------

* modify content xml of variable sr, to meet a special webservice.
* added eventListener to get upload process of files

    * ex: to get the value of send process.

    ```
    window.addEventListener('printerProgress', function (e: any) {
        console.log("value: " + e.detail.upload + "%");
    });
    ```
