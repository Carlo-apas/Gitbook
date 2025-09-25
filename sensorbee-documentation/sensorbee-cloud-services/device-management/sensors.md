# Sensors

The Sensors tab allows you to view and manage the sensors connected to your device. You can see a list of all the sensors that are currently connected, as well as information about each sensor's type, sensor values, and last update.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkZiMmRkOTU5ZS03Y2UwLTQ3ZDctOTQxZC00NGQ4ZWVjZjNjNjYlMkZpbWFnZS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MTc1ZDliODMtY2NhYy04MGIzLWIxODUtZTE2ZDBiOTRlNGE2JmNhY2hlPXYyJndpZHRoPTEyMTguNzc1MDI0NDE0MDYyNQ==" alt="Image without caption"><figcaption></figcaption></figure>

Figure 1 - Connected SensorsThis tab also shows the tag information if your sensors are connected to your device using a tag. It consists of a list that displays the tag serial, family type, preheat, version and production year.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkZhMjY5NGE3YS05ZWU4LTQ5NDMtOTE4Ny0xNjQ2MjQ0NTE2MDclMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NmIyZGIwMGUtYjA0Ny00MTJlLTlkMzQtNjM0NWZkYzVlNzVjJmNhY2hlPXYyJndpZHRoPTEyMTUuODc1" alt="Figure 2 - Tag information"><figcaption><p>Figure 2 - Tag information</p></figcaption></figure>

Additionally, this tab also includes the configuration setting for Particle and Gas Sensors. However, these settings are only available if you have Particle or gas sensors connected to your device.

#### Available Particle Settings: <a href="#id-29b572867660426ba553452900cefb64" id="id-29b572867660426ba553452900cefb64"></a>

The following are the available configuration settings for Particle sensor:

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkY0MTZkZDA1My02ZDEwLTRiNjktYTQ2NC0yY2UwOWM2YzRhNDIlMkZpbWFnZS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MTc1ZDliODMtY2NhYy04MGUzLWEzNjktZDljZTc4YjM5ZGIxJmNhY2hlPXYyJndpZHRoPTEzNDQ=" alt="Image without caption"><figcaption></figcaption></figure>

Figure 3 - Particle Settings

* Always On
* Keep particle sensor running all the time, this will enable an increase in how often the particle sensor can be read. _NOTE: This will increase power consumption, external power source is recommended._
* Average
* Number of sample results that are collected and averaged before updating the final sample value. _NOTE: Higher values increase the sampling time of the sensor._
* Fan Cleaning Interval
* Sensor fan cleaning interval time. Value should be in seconds.
* Offset Constant
* Offset constant for the particle mass values.
* Offset Factor
* Offset factor for the particle mass values.
* Sampling Time
* How much time it takes to collect a sample from the particle sensor.

#### Available Gas Settings: <a href="#id-133bda3f837b46dab28d45a7a49097b2" id="id-133bda3f837b46dab28d45a7a49097b2"></a>

The following are the available configuration settings for Gas sensor:

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkYxNmFkYWVhMi03YmYxLTRhODYtYmNjNC04ZTBlYzJkMTNmYzglMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9YTA0MzMyMmItYTQyZC00NDM4LWE2NWEtMjNlNWRkMDZhYTc0JmNhY2hlPXYyJndpZHRoPTEyMTUuOTc0OTc1NTg1OTM3NQ==" alt="Image without caption"><figcaption></figcaption></figure>

* Always On
* Keep gas sensor running all the time, this will enable an increase in how often the gas sensor can be read. _NOTE: This will increase power consumption, external power source is recommended._
* Offset Constant
* Offset constant for the output value of the gas sensor.
* Offset Factor
* Offset factor for the output value of the gas sensor.
* Sensitivity
* Sensitivity factor in nA per ppm.
* Temperature Compensation
* Flag that enables / disables temperature compensation for the gas sensor.
* Zero Current Offset
* Zero current offset in nA.
