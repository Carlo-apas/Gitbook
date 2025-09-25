# Firmware Update Menu

Follow these steps to enter Firmware Mode (as described in the following image):

* Select Firmware Update from the main menu by pressing 4 on the keypad.
* Once in the firmware update menu, you will be prompted to enter the update mode by selecting Y or to return to the main menu by selecting N.

<mark style="background-color:orange;">⚠️It is critical to ensure that your Modbus unit is connected to a stable power source before entering firmware update mode.This will help prevent potential issues or errors during the update process.Your computer's USB input should provide enough power for the firmware update to complete successfully. If you encounter any errors during the process, try repeating the steps or contacting technical support for assistance.</mark>

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkZmN2JlM2VlNi1lNmNiLTQ1YjItOWEwYi01NjBmODViYzc0YTklMkZTY3JlZW5zaG90XzIwMjMtMDYtMTVfMTYwOTE0LnBuZz90YWJsZT1ibG9jayZzcGFjZUlkPThhOWFlZDA2LWY4NDQtNGRlNC1iOTZiLWMxNTI2OTMxYzU1NyZpZD0xZDJkOWI4My1jY2FjLTgxZDYtOGQ3NC1lOTcxNmM2NGM0NjgmY2FjaGU9djImd2lkdGg9MTEwNC43NzUwMjQ0MTQwNjI1" alt="Image without caption"><figcaption></figcaption></figure>

When the user selects Y to enter update mode, a new menu will appear. The terminal will print out infinite C characters until the XMODEM transfer process is initiated.\
If you need to cancel the process, press any key. After 10 seconds, a failure message will appear, and you will be taken back to the main menu.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGczMtdXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkZzZWN1cmUubm90aW9uLXN0YXRpYy5jb20lMkY0YTkxMGM1MS1lNTYxLTRjN2EtODVkMC1jNWI3NmExZDhlOGMlMkZTY3JlZW5zaG90XzIwMjMtMDYtMTVfMTYwOTIzLnBuZz90YWJsZT1ibG9jayZzcGFjZUlkPThhOWFlZDA2LWY4NDQtNGRlNC1iOTZiLWMxNTI2OTMxYzU1NyZpZD0xZDJkOWI4My1jY2FjLTgxZTYtOWQ5NC1kYzhhMmE3OGZjNmMmY2FjaGU9djImd2lkdGg9MTEwNC43NzUwMjQ0MTQwNjI1" alt="Image without caption"><figcaption></figcaption></figure>

To initiate the firmware update from Tera Term go to File → Transfer → XMODEM → Send…

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkYyMjZkN2ZkYy1iOWI5LTQxOTQtYmM2Ny0zMWZkM2EwZmRjOGUlMkZTa3JtYmlsZF8yMDIzLTEwLTE2XzA4NTY1NC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MWQyZDliODMtY2NhYy04MTYxLWJlY2ItZTkyODc1ZjVjOWRkJmNhY2hlPXYyJndpZHRoPTEzNTI=" alt="Image without caption"><figcaption></figcaption></figure>

Find and select the firmware file and click open.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkY2ODFhZWRkOC0yOTY4LTQ1NjktYWNhYi0wNDIzZWE3NjUzOTYlMkZTa3JtYmlsZF8yMDIzLTEwLTE2XzA4NTczNS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MWQyZDliODMtY2NhYy04MTE3LTlhNDYtZjI3OGJiYjQ4MmRjJmNhY2hlPXYyJndpZHRoPTEzNTI=" alt="Image without caption"><figcaption></figcaption></figure>

After these steps, a new window will appear, showing the transfer progress. Simultaneously, the device's LED light will blink in a light blue color to indicate the ongoing transfer.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkZjYTU2MjUxYS0wNmRlLTRkY2YtYjRlNy1kZGQ2NDdkZGM3NTUlMkZTa3JtYmlsZF8yMDIzLTEwLTE2XzA4NTkxNS5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MWQyZDliODMtY2NhYy04MTZhLWI1NzgtYzA1NjgyYTE1ZTJlJmNhY2hlPXYyJndpZHRoPTEzNTI=" alt="Image without caption"><figcaption></figcaption></figure>

After the transfer is complete, the device will automatically reboot in 10 seconds. The subsequent boot-up might take longer than typical due to the firmware update process. Once updated, the new firmware version will be visible in the menu. To view this, press the "ESC" key to refresh the menu. If the firmware update does not succeed, an error message will appear in the terminal window. Should this occur, you may attempt the update once more. However, if the issue persists, please reach out to our support team for assistance.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkY2OGY4N2MxYy1kNmViLTQwZmYtODQxOC1jM2ViNjc0YTY4MTElMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9MWQyZDliODMtY2NhYy04MWE4LTkzNDktZjY0YjJmOWYwNzlhJmNhY2hlPXYyJndpZHRoPTExMDI=" alt="Image without caption"><figcaption></figcaption></figure>

\
