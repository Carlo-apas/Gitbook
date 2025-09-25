# Sensorbee Air Pairing Process

The Sensorbee Air pairing process involves several steps to connect your device to the platform. One of the essential procedures in this process is the LWM2M bootstrapping.

LWM2M bootstrapping is a way to establish a secure connection between the device and the platform. It allows the device to join the network and perform secure communication with the platform.

During the bootstrapping process, the device sends a bootstrap request to the platform. The platform then sends back a bootstrap response containing a set of security credentials. These credentials are necessary for the device to authenticate itself to the platform and establish a secure channel.

Once the device receives the security credentials, it can use them to perform secure communication with the platform. The LWM2M protocol provides end-to-end security for device-to-platform communication, ensuring that data is transmitted securely and reliably.

In summary, LWM2M bootstrapping is a crucial step in the Sensorbee Air pairing process that establishes a secure connection between the device and the platform. It is necessary to ensure that the device can join the network and perform secure communication with the platform.

***

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkZkN2YwMGFhNS1lZDk1LTQyNzUtYTE3YS1hYzI2MTk0Mjk4ZWYlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9ZGI1NzI1M2YtMjBlNC00ZDIyLWFlODMtYjQ2OWRlZjM0MGRkJmNhY2hlPXYyJndpZHRoPTE0MTUuOTg0Mzc1" alt="Image without caption"><figcaption></figcaption></figure>

#### Types of Bootstrapping <a href="#b31cd771cf764aebbf62cb95a86f7ee7" id="b31cd771cf764aebbf62cb95a86f7ee7"></a>

There are two types of bootstrapping a device. Please refer below for details:

* **Sensorbee** - A process that will bootstrap a device to Sensorbee’s internal LwM2M server and will require login access to Sensorbee’s cloud portal. Once the device is bootstrapped and paired successfully, the device will then report to our internal server and eventually its data will be shown in the portal’s dashboard.
* **External** - A process that will bootstrap a device to an external LwM2M server and differs from the type “internal” because this will NOT pair the device to Sensorbee’s LwM2M server. It also means, the user is expected to have an available LwM2M server outside of Sensorbee. Additionally, this process will not make use of the Sensorbee’s cloud services, therefore, the device cannot be managed from the cloud portal. This is useful if the user only wants to buy the device and sensors from us, but not interested in using our cloud services.

[Sensorbee](https://docs.sensorbee.com/sensorbee-air-product-manual/sensorbee-air-pairing-process/sensorbee)

[External](https://docs.sensorbee.com/sensorbee-air-product-manual/sensorbee-air-pairing-process/external)
