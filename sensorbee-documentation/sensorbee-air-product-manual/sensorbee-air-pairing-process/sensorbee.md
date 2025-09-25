# Sensorbee

This section describes the process and parameters needed when bootstrapping a device to Sensorbee’s LwM2M Server.

#### Scanning the QR Code <a href="#id-0a49fb333d6b40a6ab1a026905f3cbe6" id="id-0a49fb333d6b40a6ab1a026905f3cbe6"></a>

When you scan the QR code from the sticker attached in your device, you will be redirected to this url: [https://console.sensorbee.com/setup/](https://console.sensorbee.com/setup/aol30di)\<peeringcode>Step 1: If you are NOT logged-in, you will be prompted with this message:

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkY3MzZkYWViNS05MWEyLTQzNGItODUyMS0yYmUxNTc0ODgyM2YlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MmM5NmNkNTEtNjJhMS00NTc2LWFmNTMtMjUwZGY0MGE5M2IwJmNhY2hlPXYyJndpZHRoPTExMDEuOTc0OTc1NTg1OTM3NQ==" alt="Image without caption"><figcaption></figcaption></figure>

Step 2: Since this section talks about Sensorbee, you will select “Use Sensorbee LwM2M”. Then you will be redirected to the login page. You’re required to login so your device will be registered to your account. _(Note: If you are already logged-in before you scanned the QR, step 1 and 2 will be skipped)_

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkZiZjhkNDZlNi0xNWI4LTQxZjItOTVjNy04MTM2ZTJlYjVmNTglMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MmU0OWFkZDEtNzkzNy00ZWU4LTk3M2ItZjRjNTAxYTQ1OTI3JmNhY2hlPXYyJndpZHRoPTEwNzg=" alt="Image without caption"><figcaption></figcaption></figure>

Step 3: Once login, you will be redirected to the setup page. The Peering ID and the endpoint name will be prefilled for you, so all you need to enter is the Installation ID and name you want to assign to the device.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkZlNjliNjFiZS0yZWZlLTQ0ZTctODM0ZS0wZWY1NjhiMWFhZDIlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NTAzMTgyM2EtMTIyMS00MTY3LThjNmItNTZmZGJmMzA2NDkzJmNhY2hlPXYyJndpZHRoPTEyNDg=" alt="Desktop View"><figcaption><p>Desktop View</p></figcaption></figure>

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkYwZTcwOWExYi1lMzhmLTQ0YmItOGM2Zi1iOTllMzdjY2U0YTAlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NWFhYWE2ZGItMWEwMC00OWE0LWE0YjAtOTVlYmUzNDIzNDFhJmNhY2hlPXYyJndpZHRoPTQ4MA==" alt="Mobile View"><figcaption><p>Mobile View</p></figcaption></figure>

Step 4: In this step, you will be shown with the LwM2M server details such as the server url, security mode and Pre-shared key. By default all of these are prefilled for you so you don’t have to do anything, unless you want to change the value of the Pre-Shared Key. Also, since you selected “Use Sensorbee LwM2M” you may notice that the LwM2M server is set to “Sensorbee AvSystem”.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkY3NDJkMzAwMS0xYjFmLTQwYzQtYTQ0OS04OTJlNDg1NzIzNTQlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MWM3NTllOWYtNjNmMy00MDIwLWI0ZTgtZTRmOTY2NmExMmViJmNhY2hlPXYyJndpZHRoPTExMDQuNzc1MDI0NDE0MDYyNQ==" alt="Image without caption"><figcaption></figcaption></figure>

Step 5: This step is for the summary of details. You may review the details before you click submit.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkYzNTEyOTkwZC0wMGVmLTQzZTUtODY5Ni0wYzVlOGQzYzVkMzQlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MTUyZjRiNzYtYjAxMy00OThhLWIwZDQtZTkzODA2MDI3NTU0JmNhY2hlPXYyJndpZHRoPTExMDQuNzU=" alt="Image without caption"><figcaption></figcaption></figure>

Step 6: After you click submit, the bootstrap process will start. Once done, you will see these prompts:

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkY4Mjc3OTljMS1mNTBjLTQ5YTMtYjFhMS1jNjY3MjI0ZmM1Y2IlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NjVmMzZhY2UtNjUzOC00MWU2LTlmYjYtOTQwYzdkM2ZjZmI1JmNhY2hlPXYyJndpZHRoPTgzMg==" alt="Image without caption"><figcaption></figcaption></figure>

Step 7: Now all you need to do is to turn on the device for it to start sending values.

#### Additional Information: <a href="#id-38d06ca4779d4125bc095e65f6d6470c" id="id-38d06ca4779d4125bc095e65f6d6470c"></a>

The process shown above is by scanning the QR code. However, in the dashboard you can also add a new device without scanning. Just go to the “Devices” page and click the “Pair” button at the top-right of the screen.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkZkYzI4NjFlYi0wZjFhLTRjYWQtODRiZi0yZjYyZDA0NDY4MzElMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NjgzM2Q3OGItMzIxYi00MjlhLWJjM2MtODQ1YTQ1ODY1Y2U1JmNhY2hlPXYyJndpZHRoPTExMDQuNzI0OTc1NTg1OTM3NQ==" alt="Image without caption"><figcaption></figcaption></figure>

\
