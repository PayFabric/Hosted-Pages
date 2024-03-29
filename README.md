PayFabric Hosted Pages
======================
PayFabric hosted pages are secure pages that can be embedded into your application, to allow for processing of the transactions or creating new credit card or eCheck entries into a customer’s wallet. Below are the base URL:

1. Live Server:      ``https://www.payfabric.com/Payment/Web``
2. Sandbox Server:   ``https://sandbox.payfabric.com/Payment/Web``


Where do I start?
-----------------

Want to get started with PayFabric Hosted Page integration? Here's a quick check list:

1. Register and then configure a PayFabric account, check out the [Guide](https://github.com/PayFabric/Portal/tree/master/PayFabric/Sections/Configure%20Portal.md) to learn how.
2. Read up on how to generate a [Security Token](Sections/Security%20Token.md) as our hosted pages require this. 
3. Choose the hosted page you need to work with.
4. Have a question or need help? Contact <support@payfabric.com>.


Payment Page
------------

The payment page is used for embedding a page to process an existing transaction.

We have a [detailed guide](Sections/Payment%20Page.md) for getting started with embedding the payment page into your application.

Mobile Hosted Payment Page
--------------------------

The mobile hosted payment page enhances user experience by providing a seamless mobile experience on a variety of mobile devices.

We have a [detailed guide](Sections/MRHPP.md) for getting started with embedding the new mobile payment page into your application.

Wallet Page
-----------

The wallet page is used for embedding a page to create or modify credit card or eCheck entries.

We have a [detailed guide](Sections/Wallet%20Page.md) for getting started with embedding the wallet page into your application.

Mobile Hosted Wallet Page
-----------

The mobile hosted wallet page is used for embedding a page to create or modify credit card or eCheck entries on mobile or tablet devices.

We have a [detailed guide](Sections/MRHWP.md) for getting started with embedding the wallet page into your application.

Gateway Profile Page
-----------

The gateway profile page is used for embedding a page to create or modify gateway account profile.

We have a [detailed guide](Sections/Gateway%20Profile%20Page.md) for getting started with embedding the gateway profile page into your application.

Customize Page
--------------

Both the payment and wallet pages are able to be customized with a custom theme consisting of custom CSS and JavaScript, which will be inserted into and applied to the hosted pages.  We have a [guide](https://github.com/PayFabric/Portal/blob/master/PayFabric/Sections/Themes.md) for creating and using these customized themes.

Payment Terminals Signature Page
-----------

The Payment Terminals Signature page is used to retrieve the PNG version of the signature for the transaction created from Payment Terminals.

We have a [detailed guide](Sections/Payment%20Terminals%20Signature%20Page.md) for getting started with embedding the signature page into your application.

Retrieve Response
-----------

When you embed a payment/wallet hosted page in a Windows Forms application, you may need to retrieve the response from the hosted page for the Windows Forms application,

We have a [detailed guide](Sections/Retrieve%20Response.md) for retrieving response of embedded hosted pages in your Windows Forms application.

Help us make it better
----------------------
Please tell us how we can make the Hosted Pages better. If you have a specific feature request or if you found a bug, please contact <support@payfabric.com>. Also, feel free to branch these documents and send a pull request with improvements!

Versions
------------
For our other supported versions of the Hosted Page please see the below:

* [Version 2.0](https://github.com/PayFabric/Hosted-Pages/tree/v2)
