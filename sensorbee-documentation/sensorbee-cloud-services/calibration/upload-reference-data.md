# Upload Reference Data

This page allows user to easily import sensor data from reference station / device that will be used for calibrating a sensor. The user can import a file in .csv, .xlsx or .xls and must contain the necessary columns to properly map data to our database. This document will explain the process of how to import data correctly to our system.

#### Importing Reference Data <a href="#d743e6616c8948b9b666e19c6f4808cd" id="d743e6616c8948b9b666e19c6f4808cd"></a>

Step 1: Go to “Calibration” page and select the “Reference Data” tab.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkY3OWNiNzgyYy1kYmZlLTQxMmItYTI4Mi1jM2Y3YjI3NDQxNzElMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9Y2YwMzllMjItMGE1My00ZjY0LWFhOTEtMzVkMjcxMjdkMzU2JmNhY2hlPXYyJndpZHRoPTE0MTUuOTU5OTYwOTM3NQ==" alt="Figure 1 - Reference Data tab"><figcaption><p>Figure 1 - Reference Data tab</p></figcaption></figure>

Step 2: You have the option to enter a remarks or description as additional reference to the set of data that you are about to upload. You can leave the field blank if you opted not to provide any remarks or description.Step 3: Click the “Browse File” button. Then, a modal will appear.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkYyYjhhMWY1MS1kZDQ1LTQ2YzktYWEzNS0wZjkxZTU5ZTE4OGQlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NjBkOTllZTEtZDYxYS00OThlLWI4ZDktOTVhNzNkOTNkYjM1JmNhY2hlPXYyJndpZHRoPTE0MTUuOTc5OTgwNDY4NzU=" alt="Figure 2 - Browse File Modal"><figcaption><p>Figure 2 - Browse File Modal</p></figcaption></figure>

Step 4: Browse / look for the file that you want to upload, or you can simply drag it into the screen.Step 5: Once found, the modal will show the file preview and will ask you to select a “Header Row”.

* Header row means, the row where the column header names are found. Please take note that this depends on how the content of your file is arranged or formatted. In this example the file has extra 2 rows (_row 1 and 2_) before the column header row.
* Once done, click “Next”.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkZjODI4YzYyMS1jZGM5LTQ3OTYtYjk5OC0xYzJkOTIyOWZjNDclMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9Nzc4MDM2NzgtMmYzYy00NzBjLThhYTItYTQ4OTIxYjUzZWRhJmNhY2hlPXYyJndpZHRoPTE0MTUuOTU5OTYwOTM3NQ==" alt="Figure 3 - Select Header Row"><figcaption><p>Figure 3 - Select Header Row</p></figcaption></figure>

Step 6: In this step you will be asked to map the file columns to our database columns. Please take note of the required fields:

* Date & Time - Must follow the format YYYY-MM-DD hh:mm
* Sensor Name - Please follow the proper sensor naming below:
* NO2
* CO2
* O3
* SO2
* PM10
* PM2.5
* Sensor Values - The numeric value of the sensor reading.
* Station - The reference station name or reference device name.
* Unit - The unit of measurement. The system accepts the following:
* ppb
* ppm
* µg/m3

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkYwMmJkNWNkMS04NWJkLTRlZmUtOTg1OS04MWU1ODNmMzBjNjYlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NzFjZWViZmYtNTU3Ni00MmI1LWE3N2MtYTdjNjM2ZjA2N2JhJmNhY2hlPXYyJndpZHRoPTE0MTUuOTU5OTYwOTM3NQ==" alt="Figure 4 - Map Columns"><figcaption><p>Figure 4 - Map Columns</p></figcaption></figure>

Step 7: In this step you will be asked to verify the data before uploading to the server. If any of the columns does not follow the proper or required format, an error message will be shown in the screen. If there’s none, then you are good to go. Click “Submit” once you’re done verifying.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkY3OWJmODc5Yi0yNTg5LTRiYjctYTJjNi00ODk3NzU0NGIwN2ElMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9YWNiNjZhNGEtYjMyMy00MjU4LTliYTItOWMzMzA0YWRjZjYxJmNhY2hlPXYyJndpZHRoPTE0MTUuOTc5OTgwNDY4NzU=" alt="Figure 5 - Verify Data"><figcaption><p>Figure 5 - Verify Data</p></figcaption></figure>

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkZjOWM4ZDI2OC0xMjVlLTRkY2MtYWY4Ni1mYTEwZDNhNzJhOGYlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9NWY0ZjczODYtODY2Zi00MmEwLWE5NmMtMTlhOTQ5MTFhOWI5JmNhY2hlPXYyJndpZHRoPTE0MTUuOTU5OTYwOTM3NQ==" alt="Figure 6 - Processing Data"><figcaption><p>Figure 6 - Processing Data</p></figcaption></figure>

Step 8: Wait for the process to finish and the “Success” message.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkZiNmNiNzI5NC02NzRlLTQ2YTYtYTI4OS1jNjFmMTMxZTgyNWElMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9YTMyNDk0ODItMzBlOS00OWRmLThlYmMtZjkwZjYyYWE4ZGMwJmNhY2hlPXYyJndpZHRoPTE0MTUuOTU5OTYwOTM3NQ==" alt="Figure 7 - Successful Upload"><figcaption><p>Figure 7 - Successful Upload</p></figcaption></figure>

Step 9: You should be able to see a list of uploaded data per reference station / device on the “Available Reference Stations / Devices” grid below.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkY5NDdkN2VlYi00OTdmLTQwMWUtODZjMC0zNjg1NjlhZDcyNDIlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MWQwMTQxNjQtN2Q0MC00NWU3LWJhNjctYTdhYjQ0OGEyMDlmJmNhY2hlPXYyJndpZHRoPTE0MTUuOTc5OTgwNDY4NzU=" alt="Figure 8 - Available Reference Stations / Devices"><figcaption><p>Figure 8 - Available Reference Stations / Devices</p></figcaption></figure>

Step 10: You can now use the reference data in the calibration steps.
