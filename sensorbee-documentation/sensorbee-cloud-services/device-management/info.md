# Info

The device Info tab provides users with detailed information about the device. This includes the device name, serial, manufacturer, firmware version, registration date and other important identifiers. Users can also view information about the device's connectivity status and power usage.In addition to these basic details, the Info tab may also display more advanced information about the device's functionality. This could include settings for customizing the device's behavior, such as adjusting the polling interval which instructs the device on how often it should communicate with the server.

#### Sections and Parameters <a href="#a425d258224748ab8ac14f23afefc8cc" id="a425d258224748ab8ac14f23afefc8cc"></a>

The info tab is divided into several sections. Please refer below for details:’

* Status
* This section shows the registration status of the device, the last seen time, and the battery level.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkYwYjEyMzNhOC1lZjY2LTRmYmQtYTgyOS0xNDM5N2U3ZDk2YTMlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NDAwZTI2NWQtNDFjNi00NGI3LThjODgtYmYyZmZmNDFlMDM0JmNhY2hlPXYyJndpZHRoPTE0MTUuOTM3NQ==" alt="Figure 1 - Device Status"><figcaption><p>Figure 1 - Device Status</p></figcaption></figure>

* Connectivity
* This section shows the connectivity parameters of the device, such as network information and signal strength.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkY4NmYwYzNiZS1mNDkxLTQ1NGQtYmJjNy0xZDRkYTk1MzAxMzQlMkZpbWFnZS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MTc1ZDliODMtY2NhYy04MDkzLWI2NjItZDAwNzI0YzdmYWZjJmNhY2hlPXYyJndpZHRoPTE0NDA=" alt="Image without caption"><figcaption></figcaption></figure>

Figure 2 - Connectivity

* Device Info
* This section shows information pertaining to the device definition in the LwM2M server such as Endpoint Name, Server Identity, Security Mode, Serial, Registration Date, and many more.
*

    <figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkYyM2M1N2U5YS0wOWE5LTRkNDctOGVkOC04N2YxOTZmYzE4NzMlMkZpbWFnZS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MTc1ZDliODMtY2NhYy04MDdjLWE3ZjAtZTBjNjRlNzcyNDQwJmNhY2hlPXYyJndpZHRoPTExNTI=" alt="Image without caption"><figcaption></figcaption></figure>
* Figure 3 - Device Info
* Integration
* This section allows you to assign Push API integration to the device. Once assigned, the sensor value payload that the device reports every interval to the server, will also be forwarded to the Push API endpoint. To know more about how to setup a Push API, kindly refer to [Integration Push API.](https://docs.sensorbee.com/sensorbee-cloud-services/integration/push-api)
*

    <figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkY3YTU3ZDZkMy02NWMwLTQ4ZTQtOWYwMy0xZGRmMzM3Mzg3NGQlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NWI5OGM3MGQtY2JhNC00Y2E1LWI1YjYtNzcyNmFlMzM1ZmVjJmNhY2hlPXYyJndpZHRoPTEzNTkuOTUzMTI1" alt="Figure 4 - Integration"><figcaption><p>Figure 4 - Integration</p></figcaption></figure>
* Device Settings
* This section shows the different device settings available for viewing and updating. Each setting can affect the device behavior therefore not all of these can be updated from the portal. However, important settings like polling interval, nighttime start, remain to be updatable.
*

    <figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkY5MjI2NmYxNy0wNjNkLTQ5ZjUtOWQwMS03ZmZmNGYyNGY2ODglMkZpbWFnZS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MTc1ZDliODMtY2NhYy04MDhmLTlmYmUtZmVmZjYwNDk0NTI5JmNhY2hlPXYyJndpZHRoPTExNTkuOTUwMDczMjQyMTg3NQ==" alt="Image without caption"><figcaption></figcaption></figure>
* Figure 5 - Device Settings
* #### Available Settings: <a href="#id-5f6f41b7d9c14d79b7a133265284f4c3" id="id-5f6f41b7d9c14d79b7a133265284f4c3"></a>
* The following are the available device settings:
* Low Power Threshold
* The threshold battery level, upon being reached, triggers the Base Unit's transition into a low power mode.
* Maximum Charge Current
* Maximum charge current for charging the battery.
* Nighttime Duration (hour)
* The duration of the nighttime in hours.
* Nighttime Start (hh:mm:ss)
* Scheduled onset time for nighttime, where the time is given in the following format (hh:mm:ss) UTC. Otherwise, set as 0 to disable.
* Polling Interval (sec)
* The default polling interval that the device follows when polling sensor value and reporting to the server. Value should be in seconds.
* Polling Interval (Low Power) (sec)
* Polling interval during low power mode. Value should be in seconds.
* Polling Interval (Nighttime) (sec)
* Polling interval during the nighttime. Value should be in seconds.
* Noise Sensor Key -A unique identifier assigned to a noise sensor within the air quality monitoring system. This key is used to distinguish and manage data from multiple noise sensors across different locations in the cloud platform.
* Polling Offset - The time delay or interval adjustment applied to sensor data polling schedules. This feature ensures that sensor data collection is staggered or optimized to prevent network overload, ensure system efficiency, or align with specific operational requirements.
* Catch Up Rate -The rate at which a sensor or system processes and synchronizes previously missed or delayed data to align with the current real-time data stream. This ensures accuracy and completeness of historical data without overwhelming the system.
* Device Logging -The process of recording and storing detailed operational data from devices, including sensor readings, status updates, error logs, and diagnostics. Device logging enables performance tracking, troubleshooting, and compliance with regulatory requirements.
* Important Note
* When updating a value of a setting, the change won’t be reflected right away, as the server would still wait for the next interval before the change would be applied to the device. A note that says “Found pending change” will be displayed under the setting field, when a previous change is not yet applied.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkYxODQxNDA5ZC1lMjkzLTQ1OWItYWFiNS00N2FmOWY4Yjg4ZmYlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9OTE1NTQyODAtNjNmNi00NzJmLWIzOTQtN2U4MGM4Y2Y4YWJkJmNhY2hlPXYyJndpZHRoPTEyMTguNTUwMDQ4ODI4MTI1" alt="Figure 6 - Pending note"><figcaption><p>Figure 6 - Pending note</p></figcaption></figure>

\
