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
## 11.0.0 (2017-08-30)


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
* **payment:** Do not remove braintree instances from $window 
* **payment:** Do not try to create Data Collector if Kount is disabled 
* **payment:** Handle Braintree data collector errors

### Features

* **payment:** Add PayPal credit button text and image
* **payment:** Surface PayPal Credit on checkout
* **payment:** Add button text + loader service for VisaCheckout
* **payment:** Add tests for Braintreevisacheckout.controller
* **payment:** Rename VisaCheckout controller to avoid braintree collision
* **payment:** Surface VisaCheckout

<a name="10.1.1"></a>
## 10.1.1 (2017-08-18)


### Bug Fixes

* **address:** Avoid show billing address information or message before loading remote address data

<a name="10.1.0"></a>
## 10.1.0 (2017-08-18)

### Bug Fixes

* **http-request:** Handle lower-case response headers
* **payment:** Fix teardown handling for dataCollector and threeDSecure 

### Features

* **payment:** Create service for injecting deviceData into quote
* **payment:** Make braintreeLoader to always create dataCollector instance
* **payment:** Use dataCollector service in braintree controller
* **payment:** Use dataCollector service in braintreepaypal controller

<a name="10.0.0"></a>
## 10.0.0 (2017-08-15)


### Features

* **data-store:** Add a module responsible for storing data
* **http:** Add a module responsible for making HTTP requests
* **vco:** Introduce the Edit with Visa Checkout option

<a name="9.3.1"></a>
## 9.3.1 (2017-08-07)


### Bug Fixes

* **forms:** Include Object.assign polyfill for Custom Form Fields
* **order:** Handle empty XHR responses when deviving error messages



