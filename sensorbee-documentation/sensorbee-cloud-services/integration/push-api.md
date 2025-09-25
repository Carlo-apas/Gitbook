# Push API

The Push API provides real-time forwarding, allowing users to receive data from Sensorbee in real-time as it is posted in the server. This type of integration is useful for applications that require up-to-the-moment data, such as those used for monitoring or tracking environmental parameters. By using the Push API, users can receive data as it is posted in the server, without needing to rely on periodic polling or other less efficient methods.

#### Needed Parameters: <a href="#b50dc078839f4c1792fcb5b4e3a27cf8" id="b50dc078839f4c1792fcb5b4e3a27cf8"></a>

* Push API Name (Required)
* The name you want to call your push API (example: “Station 1 Push API”).
* Endpoint URL (Required)
* An HTTP POST endpoint, where the push API payload will be sent.
* Description (optional)
* Any description that you can think of.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkZmYjVlNTZkZS0wOWJlLTQ4NzAtOGU3YS0yMGZkZDc1ODhlN2IlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NmJlMzZhY2ItNTI1ZC00NjczLThlNGYtMjgxMjA2OGY0ZTE3JmNhY2hlPXYyJndpZHRoPTExNjcuOTUwMDczMjQyMTg3NQ==" alt="Figure 1 - Create Push API Step 1"><figcaption><p>Figure 1 - Create Push API Step 1</p></figcaption></figure>

* Header Params (Optional)
* In case your endpoint requires some header parameters like “apiKey” or “Bearer” token, you can add them in the Headers grid on a key-value pair order.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkYyNDFkZmVjMS03NjA1LTQ5YjYtYTI2Ni1iOTgzMmZjZTRjY2UlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9ZDRhNmM1OGQtYjA3ZC00MjkyLTgxZDEtYjMzMzFjNmFhZDM5JmNhY2hlPXYyJndpZHRoPTEyMTUuOTc0OTc1NTg1OTM3NQ==" alt="Figure 2 - Create Push API Step 2"><figcaption><p>Figure 2 - Create Push API Step 2</p></figcaption></figure>

After the Push API is created, you can now assign it to a base unit. Please see[ Device Management Info](https://docs.sensorbee.com/sensorbee-cloud-services/device-management/info#df66f29fbb9a4210b3547863032cf0e3) for details on how to assign an integration to a base unit.

#### JSON Payload <a href="#c3d0c6601df542a5a2f3f09f08faf436" id="c3d0c6601df542a5a2f3f09f08faf436"></a>

When the push API is successfully assigned to a base unit / device, a JSON payload will then be forwarded to your endpoint every polling interval. The content of the JSON payload uses the [Smart City Template](https://docs.sensorbee.com/sensorbee-cloud-services/integration/smart-city-template), which contains all significant parameters needed for monitoring the air quality and the environment.
