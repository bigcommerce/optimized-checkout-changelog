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



