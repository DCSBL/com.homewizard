# HomeWizard

Upon first deployment you need add the Homewizard unit first, then you can add the related/connected components from Homewizard to your Homey.

NOTE! - ENABLE "LOCAL API" FOR YOUR ENERGY SOCKET FIRST IN THE OFFICIAL HOMEWIZARD ENERGY APP

v2.1.30
* Homewizard context/preset fix

v2.1.29
* Heatlink fix - function error

v2.1.27
* Homewizard Energy - Watermeter support
* Dropped AbortController implementation (prone to memory problems)
* Temporary disabled precheck tcp
* Replaced node-fetch library with axios as its has easier timeout handling for Homewizard Legacy devices

v2.1.23
* Added precheck Homewizard Legacy if device is available before attempting JSON pull

v2.1.17
* Changed mdns discovery string to host kwhmeter (this will match both sdm230 and sdm630)

v2.1.16
* Adjusted mdns condition check as it was matching the wrong devices


**If you like this app, then consider to buy me a beer :)**

[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/paypalme2/jtebbens)
