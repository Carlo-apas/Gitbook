# Header

The header section is comprised of device information such as the serial no, endpoint name and the site. It serves as a general guide of the device identity as you move from one sub tab to another.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkZjMzRlODk5NS1jNmI1LTRjMmMtODNhNS0yYmUwYzFkNGUyYjElMkZpbWFnZS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MTc2ZDliODMtY2NhYy04MDdlLWJkYzQtZGZiNjAxNTQ0ODAzJmNhY2hlPXYyJndpZHRoPTEyMTguNzI0OTc1NTg1OTM3NQ==" alt="Image without caption"><figcaption></figcaption></figure>

Figure 1 - Header Section

#### Set GPS Manually <a href="#b92780386a4949e0bfa1373442c3cedf" id="b92780386a4949e0bfa1373442c3cedf"></a>

One feature that can be found here in the header section is the function to set or unset device location manually. By clicking the “GPS” button, the GPS modal window will be shown.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkY5OWY4OWMwMy04NjdhLTQzOGMtYmQ1NS01ZTk1Y2RmMmVjMjAlMkZpbWFnZS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MTc2ZDliODMtY2NhYy04MDQ4LTllYzUtZDA4YjM2MmY1YTQyJmNhY2hlPXYyJndpZHRoPTEyMTguNzU=" alt="Image without caption"><figcaption></figcaption></figure>

Figure 2 - Device Location Modal

* You can drag the marker to a location you want and then press “Set” to save the location.
* Once the location is set manually, the GPS coordinates will then be included in the report’s smart city template and in the Push API JSON payload, under the gps\_latitude and gps\_longitude parameters ([please see Report for more details](https://docs.sensorbee.com/sensorbee-cloud-services/device-management/report)). This will also set the GPS mode to “manual”.
* Please note that this manually set location will override any GPS coordinates reported by the device, which means, if your device is reporting GPS coordinates, they will be disregarded in favor of these manually set coordinates.
* In order to use the GPS coordinates reported by the device, just click the “Unset” button to remove the manually set coordinates and reset the GPS mode back to default.
* This feature is useful especially if your device is not sending any coordinates at all.
