# Firmware Update Menu

***

Follow these steps to enter Firmware Mode (as described in the following image):

* Select **Firmware Update** from the main menu by pressing 4 on the keypad.
* Once in the firmware update menu, you will be prompted to enter the update mode by selecting **Y** or to return to the main menu by selecting **N**.

⚠️ It is critical to ensure that your Modbus unit is connected to a stable power source before entering firmware update mode. This will help prevent potential issues or errors during the update process.

Your computer's USB input should provide enough power for the firmware update to complete successfully. If you encounter any errors during the process, try repeating the steps or contacting technical support for assistance.

![Screenshot 2023-06-15 160914.png](<../../../../.gitbook/assets/Screenshot_2023 06 15_160914.png>)

When the user selects **Y** to enter update mode, a new menu will appear. The terminal will print out infinite **C** characters until the XMODEM transfer process is initiated.

If you need to cancel the process, press any key. After 10 seconds, a failure message will appear, and you will be taken back to the main menu.

![Screenshot 2023-06-15 160923.png](<../../../../.gitbook/assets/Screenshot_2023 06 15_160923.png>)

To initiate the firmware update from Tera Term go to File → Transfer → XMODEM → Send…

![Skärmbild 2023-10-16 085654.png](<../../../../.gitbook/assets/Skrmbild_2023 10 16_085654.png>)

Find and select the firmware file and click open.

![Skärmbild 2023-10-16 085735.png](<../../../../.gitbook/assets/Skrmbild_2023 10 16_085735.png>)

After these steps, a new window will appear, showing the transfer progress. Simultaneously, the device's LED light will blink in a light blue color to indicate the ongoing transfer.

![Skärmbild 2023-10-16 085915.png](<../../../../.gitbook/assets/Skrmbild_2023 10 16_085915.png>)

After the transfer is complete, the device will automatically reboot in 10 seconds. The subsequent boot-up might take longer than typical due to the firmware update process. Once updated, the new firmware version will be visible in the menu. To view this, press the "ESC" key to refresh the menu. If the firmware update does not succeed, an error message will appear in the terminal window. Should this occur, you may attempt the update once more. However, if the issue persists, please reach out to our support team for assistance.

![Untitled](<../../../../.gitbook/assets/Untitled (2).png>)
