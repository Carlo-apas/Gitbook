# Map

***

The Sensorbee Map View is a feature that allows users to visualize data in a geospatial context. It provides a graphical representation of the device data on a map view. It is also designed to be user-friendly and provides a range of tools for data exploration and analysis.

Users can zoom in and out of the map, pan around to explore different areas, and click on data points for more information.

The map view also supports time-series data, allowing users to see how data changes over time. There are available sensor layers that would allow user to visualize the changes. This documentation aims to guide you on how to make use of the available controls and filters.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkYyNjRhMDkzNy1kZDM1LTQ5Y2YtYjYzMS1kYzlmNDc3ZTJmYTIlMkZpbWFnZS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MTc3ZDliODMtY2NhYy04MDc2LWExZjMtYzYxYzQ2OTAyNmQ3JmNhY2hlPXYyJndpZHRoPTEyMTguNzU=" alt="Image without caption"><figcaption></figcaption></figure>

Figure 1 - Map’s device detail

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkZiMzA3ODJlNy1kY2ZlLTRiMDktYjZiNy0xZjJiMGM0M2ZhYmIlMkZpbWFnZS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MTc3ZDliODMtY2NhYy04MGI0LWIzYWYtZWM2MDM5YmFjYmZkJmNhY2hlPXYyJndpZHRoPTEyMTguNzc1MDI0NDE0MDYyNQ==" alt="Image without caption"><figcaption></figcaption></figure>

Figure 2 - Map’s sensor layer

#### Available Features <a href="#id-9569fb281fa14776a9e10252209f5973" id="id-9569fb281fa14776a9e10252209f5973"></a>

This section talks about the features and controls available in the map view. Please refer below for your guide.

* Device List and Info - The upper right section of the map provides a list of installations / devices that you can search on and view. Once a device is selected, you would be flown towards its location (if GPS is available) and a modal, containing the device info and historical graph, will pop-up.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkZjYzQ5ZmI2OS01NDI3LTQzZDAtYjRjZi05MzUxMzcwYjU0ZTIlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NzZjZDE1MzUtMTBmMC00OGUxLTkyMGItMDAzZGQ1NmZkZTgyJmNhY2hlPXYyJndpZHRoPTEyNTIuNzU=" alt="Figure 3 - Device List and Info"><figcaption><p>Figure 3 - Device List and Info</p></figcaption></figure>

* Heatmap
* You can view the sensor heatmap by selecting from the heatmap selection on the lower-right section of the screen (please see the image below). The heatmap represents the average sensor reading and the data density gathered daily in an area. As you zoom further, sensor layers will replace the heatmap (see next bullet).

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkYwYTc2ODQzNS1mYWFmLTRmYmQtYTczOC05NmQzNGE3NTFlMzUlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9OTNjZGY2YjQtM2Y0Mi00NzU4LWJkMDItZThjNzUyY2ZjNmY2JmNhY2hlPXYyJndpZHRoPTEyNTIuNzc1MDI0NDE0MDYyNQ==" alt="Figure 4 - Heat map"><figcaption><p>Figure 4 - Heat map</p></figcaption></figure>

* Sensor Layers
* Each of your devices would be represented by a “circle” on the map, following a color coding based on the legend below. Each sensor layer has its own set of legends and color coding depending on the sensor readings.
* Additionally, you can drag the slider to see the changes of the readings over 30 days.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkY0ODBmNWZhZC0wY2EwLTQ1OWQtYmY2My01OTViNzUwYzk5ZmMlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9ODgxYTdjZDQtZDk3NS00NTFmLTk5M2EtODQxMTc0Y2EyMGZjJmNhY2hlPXYyJndpZHRoPTEyNTIuNzU=" alt="Figure 5 - Sensor Layer"><figcaption><p>Figure 5 - Sensor Layer</p></figcaption></figure>

***

Helpful?
