<properties date="2016-06-24"
SortOrder="1"
/>

![](images/devnet_logo.png) ![](expander-sdk.jpg)
Expander SDK: Server Services .net API
======================================

Documentation for NetServer 8.0
(Jun 2016)

The web-services API gives you platform-independent access to SuperOffice data and functionality.

Web-services are simple to use:

         ContactAgent ca = new ContactAgent();
         ContactEntity c = ca.GetContactById( 123 );
         System.out.WriteLine("Contact 123 has name {0}", c.Name );

Take a look at:

* [**What's new in NetServer's Services API**](What's%20New/What's%20New.md)
* [**Introduction to services: concepts**](Introduction/Introduction.md)
* [**Guide to programming with the services API**](Developer's%20Guide/Developer's%20Guide.md)
* [**Programming Examples**](Examples/Examples.md)