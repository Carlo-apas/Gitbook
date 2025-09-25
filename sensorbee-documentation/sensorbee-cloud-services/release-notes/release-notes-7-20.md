# Release Notes 7/20

We are pleased to announce new features and bug fixes in the Air Quality Monitoring Portal. Here’s a comprehensive overview of what’s new and improved.

### New Features and Improvements

*   **Support for Solar Radiation Sensor :**

    * Updated the sensor definition file for seamless integration with the portal .
    * Historical graphs now accommodate solar radiation data, providing valuable insights over time .
    * Solar radiation metrics are now available in the push API, allowing for real-time data access and system integration .
    *

    ```
      [](https://mail.google.com/mail/u/0?ui=2&ik=666f669a51&attid=0.5&permmsgid=msg-a:r-8800982873582796105&th=196e6933e465487c&view=fimg&fur=ip&permmsgid=msg-a:r-8800982873582796105&sz=s0-l75-ft&attbid=ANGjdJ84n5QSwref4p8qMf3xkoTMZZ_1o2imBu9K13tK9O5aoUDEB8t-c5stzCBiT4q0ud1j9Mo0DlvgaWHruCsGnsoxDn0HvitVFILUqfKfAo4bCFFO16ZHloaN_YY&disp=emb&realattid=ii_mauisxr25&zw)
    ```
* **Support for New External Temperature Sensor :**
  * Ensure that your temperature measurements are accurate and that reports reflect the latest sensor data.
* **Report Enhancement :**
  * Sensor units are now included in report headers for clarity and better data understanding.

### Bug Fixes

* **VOC Sensor Visibility and Computations:**
  * Resolved an issue where the new VOC sensor was not appearing in the connected sensor list
  * Corrected wrong computations for `ug/m³` values in the gas parameter tab for VOC sensors .
* **Alert and Reporting Fixes:**
  * Fixed errors in the alert log to ensure accurate logging and alert management.
  * Addressed the "invalid values" flag issue on the early warning report page to enhance report reliability.
* **System Stability and Performance:**
  * Resolved timeout errors encountered during sensor unpairing processes, improving operational efficiency.
  * Addressed missing dashboard values to ensure every data point is captured and displayed

###

###

###

### Device Research Enhancements

* **Enhanced Data Handling:**
  * Improved data retrieval processes on the device research page for faster and more reliable data access.
  * Incorporated the latest sensors to provide users with up-to-date capabilities .
* **Bug Fix for Installation Name Selection :**
  * Fixed an issue when selecting installations with identical names, improving the workflow for users managing multiple installations.
