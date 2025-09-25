# Calibration Logs

Calibration logs are important records that document the calibration process and results for different types of gas and particle sensors. Calibration is the process of comparing the measurements of a device against a known reference standard to ensure accuracy and reliability.Calibration logs typically include information such as the date and time of calibration, the type of calibration method and sensor, the computed offset constant and factor and the R² Correlation result.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkY4ZDRlNDFiMS0xZDAyLTQyYmQtOTNiOC1kMzVlNDI0NGI5ZTIlMkZpbWFnZS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MTc2ZDliODMtY2NhYy04MDE4LTlmMmUtZWQ5N2U4MjQ2NTFkJmNhY2hlPXYyJndpZHRoPTEyMTguNzU=" alt="Image without caption"><figcaption></figcaption></figure>

Figure 1 - Calibration logs

#### Available Controls and Filters <a href="#id-9aa391d319a548519f985e8db0c165e5" id="id-9aa391d319a548519f985e8db0c165e5"></a>

The following are available to filter the results of the calibration logs:

* Date/time range - The period of when you want to retrieve the calibration logs.
* Calibration Type - You can use this filter to view only the logs of specific calibration type.
* Baseline - To view only the historical logs of the baseline calibration processes applied to the sensor.
* Span - To view only the historical logs of the span calibration processes applied to the sensor.
* All - To view both Baseline and Span.

#### Result Columns <a href="#a070d5fc5c86401097a658c5a9e596d9" id="a070d5fc5c86401097a658c5a9e596d9"></a>

The following are the available columns from the log grid:

* Date and Time - The date and time of when the calibration was applied.
* Type - The type of calibration.
* Offset Constant - The offset-constant-value that is applied to the sensor after a baseline calibration.
* Offset Factor - The offset-factor-value that is applied to the sensor after a span calibration.
* Baseline Time Start & Baseline Time End - The from and to of the period when the minimum reference value has been selected for baseline calibration.
* Span Time Start & Span Time End - The from and to of the period when the maximum reference value has been selected for span calibration.
* R² Correlation Result - The preview result of the R² correlation assessment of the corrected data against the reference data, if the calibration offset will be applied (_Note: This is only a preview assessment of the corrected values, and does not necessarily reflect the actual assessment result of the values stored in the database against the reference data_).
