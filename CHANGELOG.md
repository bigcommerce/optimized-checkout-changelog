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
