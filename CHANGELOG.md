<a name="17.0.0"></a>
# 17.0.0 (2018-07-11)


### Bug Fixes

* **checkout:** Update order comments after selecting shipping option
* **common:** Upgrade build tool to fix source-map generation issue
* **common:** Use different CacheKeyResolver for each function
* **common:** Fix shopper currency
* **order:** Fetch internal order in confirmation page
* **payment:** Initialize Amazon only when logged in
* **payment:** Add copyright symbol to Chase Pay display name
* **shipping:** Check for valid shipping address after loading shipping fields
* **shopper:** Fire HandleCustomerChange when logging to Remote providers
* **shopper:** Listen for email changes in billing address


### Features

* **common:** Add wrapper methods for remaining selectors



<a name="14.2.1"></a>
## 14.2.1 (2018-01-18)


### Bug Fixes

* **payment:** Disable the Place Order button while the square forms are still loading


### Features

* **payment:** Update bcapp when storecredit is toggled
* **payment:** Allow payment with a vaulted instrument



<a name="14.2.0"></a>
# 14.2.0 (2018-01-12)


### Bug Fixes

* **checkout:** Fix calling undefined `getLoadQuoteError` method


### Features

* **payment:** Various improvements to credit card form



<a name="14.1.0"></a>
# 14.1.0 (2018-01-02)


### Features

* **shipping:** Pre-select shipping option based on BE
* **shipping:** Sort pickup in store to be last in list



<a name="14.0.0"></a>
# 14.0.0 (2017-12-19)


### Code Refactoring

* **checkout:** Extract lib folder



<a name="13.3.3"></a>
## 13.3.3 (2017-12-20)


### Bug Fixes

* **payment:** Skip payment submission if payment is already acknowledged or finalized



<a name="13.3.2"></a>
## 13.3.2 (2017-12-20)


### Bug Fixes

* **payment:** Hide credit card form if payment data is already submitted or not required



<a name="13.3.1"></a>
## 13.3.1 (2017-12-17)


### Bug Fixes

* **payment:** Fix PayPalExpress cart flow



<a name="13.3.0"></a>
# 13.3.0 (2017-12-14)


### Bug Fixes

* **common:** Add missing operators
* **common:** Ignore actions without type property
* **common:** Fix subscriber getting fired more than once if multiple filters return true
* **common:** Bump form-poster to fix callback getting called prematurely
* **coupon:** Fix coupon action assertions
* **order:** Fix mailto link on order confirmation page.
* **payment:** Fix deviceSessionId not getting passed
* **payment:** Return correct errors when paypal's tokenize step fails


### Features

* **common:** Add stored-cards component
* **payment:** Add stored instrument form to braintree
* **payment:** Post shouldSaveInstrument flag to bigpay to prompt it to vault the supplied card


### Performance Improvements

* **payment:** Load minified Paypal Express JS SDK
* **shipping:** Only load countries if needed


### Refactor

* **checkout:** Make various code improvements


<a name="13.2.1"></a>
## 13.2.1 (2017-12-15)


### Bug Fixes

* **payment:** PAYMENTS-2260 Fix PayPalExpress cart flow


<a name="13.2.0"></a>
# 13.2.0 (2017-11-22)

### Refactor

* **checkout:** Make various code improvements


<a name="13.1.0"></a>
# 13.1.0 (2017-11-20)


### Bug Fixes

* **order:** Fix getFinalizeOrderError method
* **payment:** Fix OffsitePaymentStrategy finalize condition


### Features

* **checkout:** Remove finishorder.php completely


<a name="13.0.0"></a>
# 13.0.0 (2017-10-26)


### Bug Fixes

* **payment:** Adding show/hide to the Customer Code field for Vantiv and adding 'additional context' styling per design tema request.


<a name="12.0.2"></a>
## 12.0.2 (2017-10-17)


### Bug Fixes

* **common:** Retain default request options unless overridden
* **shipping:** Avoid losing execution context for getSelectedShippingOptionId
* **shipping:** Don't throw an error if a shipping option request gets cancelled



<a name="12.0.1"></a>
## 12.0.1 (2017-10-12)


### Refactor

* **checkout:** Make various code improvements


<a name="12.0.0"></a>
# 12.0.0 (2017-10-08)


### Bug Fixes

* **billing:** Use the correct validator for billing addresses
* **payments:** Braintree on UCO - Send cardholder name
* **shopper:** Flat custom fields in customer addresses


### Features

* **shipping:** Add convertToShippingAddress method
* **shopper:** Prepopulate custom fields



<a name="11.11.0"></a>
# 11.11.0 (2017-10-04)


### Bug Fixes

* **payments:** Inform addressService that the Billing Address has been provided already (Visa Checkout)
* **payments:** Adds new PayPal Credit template for display in the Payment section of checkout



<a name="11.10.1"></a>
## 11.10.1 (2017-09-29)


### Bug Fixes

* **payment:** Use Pay Now instead of Continue button for Braintree PayPal Checkout Flow



<a name="11.10.0"></a>
# 11.10.0 (2017-09-27)


### Features

* **payment:** Send shipping methods to bigpay for CyberSource



<a name="11.9.0"></a>
# 11.9.0 (2017-09-27)



<a name="11.8.0"></a>
# 11.8.0 (2017-09-26)


### Bug Fixes

* **payment:** Map referrer id to PaymentData object


<a name="11.7.0"></a>
# 11.7.0 (2017-09-25)


### Features

* **shipping:** Improve affordance of checklists (shipping/payment selection)



<a name="11.6.0"></a>
# 11.6.0 (2017-09-25)


### Bug Fixes

* **payment:** Avoid $digest soup with timeout
* **payment:** Wrap tests in timeout


### Features

* **payment:** Widget flow through visacheckout payment step



<a name="11.5.1"></a>
## 11.5.1 (2017-09-21)


### Bug Fixes

* **payment:** Fix credit card form styling



<a name="11.5.0"></a>
# 11.5.0 (2017-09-21)


### Features

* **provider:** Add Vantiv payment provider



<a name="11.4.1"></a>
## 11.4.1 (2017-09-21)


### Bug Fixes

* **order:** Return order if cart is undefined



<a name="11.4.0"></a>
# 11.4.0 (2017-09-19)


### Features

* **payment:** Enable PayPal credit for PayPal Braintree
* **payment:** Pass PayPal method to Braintree



<a name="11.3.1"></a>
## 11.3.1 (2017-09-18)



<a name="11.3.0"></a>
# 11.3.0 (2017-09-11)


### Bug Fixes

* **common:** Better stack trace for v8 browsers
* **common:** Explicitly include es6-promise
* **data-store:** The initial action must also have type property
* **status:** Ensure loading indicator is visible while waiting for Ajax requests to complete


### Features

* **shopper:** Changes customerCreated to customerCanBeCreated



<a name="11.2.0"></a>
# 11.2.0 (2017-09-06)


### Features

* **shopper:** Add reset password error message



<a name="11.1.0"></a>
# 11.1.0 (2017-09-05)


### Bug Fixes

* **checkout:** Consistent return value for dispatch method
* **geography:** Fix the return value of fetchCountries when there is an error


### Features

* **payment:** Send orderMetaData to Big Pay
* **shipping:** Allow phone number to be optional for shipping addresses



<a name="11.0.2"></a>
## 11.0.2 (2017-09-04)


### Bug Fixes

* **payment:** Pass errors to reject and handle no response
* **payment:** Teardown Braintree on scope destroy



<a name="11.0.1"></a>
## 11.0.1 (2017-08-31)


### Bug Fixes

* **common:** Fix class name for checkoutStep



<a name="11.0.0"></a>
# 11.0.0 (2017-08-30)


### Bug Fixes

* **common:** Add missing ThemeEditor classes to allow styling
* **common:** Add ThemeEditor classes to Custom Fields
* **common:** Allow CSS to be overwritten by ThemeEditor styles
* **common:** Apply styles to form label help text: `(Optional)`
* **shipping:** Return quoteAddress because it contains the addressId


### Features

* **shipping:** Auto select when only one shipping method is available



<a name="10.1.3"></a>
## 10.1.3 (2017-08-24)


### Features

* **shopper:** Add a `finishorder.php` toggle

<a name="10.1.2"></a>
## 10.1.2 (2017-08-22)


### Bug Fixes

* **payment:** Set env to sandbox for PaypalExpress if in testMode
* **payment:** Do not remove Braintree instances from $window
* **payment:** do not try to create Data Collector if Kount is disabled
* **payment:** handle Braintree data collector errors

### Features

* **payment:** Add PayPal Credit button text and image
* **payment:** Surface PayPal Credit on checkout
* **payment:** Add button text + loader service
* **payment:** Add tests for braintreevisacheckout.controller
* **payment:** Rename Visa Checkout controller to avoid Braintree collision
* **payment:** Surface Visa Checkout

<a name="10.1.1"></a>
## 10.1.1 (2017-08-18)


### Bug Fixes

* **address:** Do not show billing address information or message before loading remote address data

<a name="10.1.0"></a>
# 10.1.0 (2017-08-18)

### Bug Fixes

* **http-request:** Handle lower-case response headers
* **payment:** Fix teardown handling for dataCollector and threeDSecure

### Features

* **payment:** Create service for injecting deviceData into quote
* **payment:** Make braintreeLoader to always create dataCollector instance
* **payment:** Use dataCollector service in Braintree controller
* **payment:** Use dataCollector service in braintreepaypal controller

<a name="10.0.0"></a>
# 10.0.0 (2017-08-15)


### Features

* **data-store:** Add a module responsible for storing data
* **http:** Add a module responsible for making HTTP requests
* **payment:** Introduce the Edit with Visa Checkout option

<a name="9.3.1"></a>
## 9.3.1 (2017-08-07)


### Bug Fixes

* **forms:** Include Object.assign polyfill for Custom Form Fields
* **order:** Handle empty XHR responses when deviving error messages
