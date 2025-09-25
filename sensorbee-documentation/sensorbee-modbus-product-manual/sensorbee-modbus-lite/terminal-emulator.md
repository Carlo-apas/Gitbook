# Terminal Emulator

***

A terminal emulator or serial monitor is required for configuring the Sensorbee Modbus base unit via its USB-C interface. In the absence of a pre-existing terminal emulator, it is necessary to download, install, and configure one. Numerous free alternatives are available for Modbus device configuration, including:

* [Tera Term (Windows)](https://ttssh2.osdn.jp/index.html.en)
* [CoolTerm (Windows, Mac, Linux)](http://freeware.the-meiers.org/)

## Download, Install & Configure Tera Term

📔 In this how-to guide, the process for downloading, installing, and setting up Tera Term—a terminal emulator used for configuring the Sensorbee Modbus unit—will be detailed.

Tera Term ranks among the leading terminal emulators for the Windows operating system. The emulator offers multi-protocol support, a tabbed user interface, and compatibility with SSH, Telnet, serial ports, as well as various file transfer protocols.

### Download Tera Term

The latest version of Tera Term can be downloaded from: [https://osdn.net/projects/ttssh2/releases/](https://osdn.net/projects/ttssh2/releases/).

ℹ️ Should this link return an error message, an alternative download site is \[https://download.cnet.com/Tera-Term/3000-2094\_4-75766675.html]\(https://download.cnet.com/Tera-Term/3000-2094\_4-75766675.html)

### Install Tera Term

Upon completion of the executable file download, initiate the installation process by double-clicking the executable.

📔 Given that the majority of installation steps principally involve advancing through the prompts by clicking the 'Next' button, a succinct enumeration of each step will be provided, deviating only if the pattern changes.

**Accept Licence Agreement**

✅ It is critical to select the “I accept the agreement” radio button before clicking \*\*Next\*\*.

![licence-agreement.png](<../../../.gitbook/assets/licence agreement.png>)

**Select Tera Term’s Destination Location**

![select-destination-location.png](<../../../.gitbook/assets/select destination location.png>)

**Select Components**

![select-components.png](<../../../.gitbook/assets/select components.png>)

**Select Language**

![select-language.png](<../../../.gitbook/assets/select language.png>)

**Select Start Menu Folder**

ℹ️ The dialogue presents an option to create a Start Menu folder. Select or deselect the checkbox based on your preference.

![start-menu-folder.png](<../../../.gitbook/assets/start menu folder.png>)

**Select Additional Tasks**

![additional-tasks.png](<../../../.gitbook/assets/additional tasks.png>)

**Ready to Install**

Click on the **Install** button, indicating that you are satisfied with all your selections.

![ready-to-install.png](<../../../.gitbook/assets/ready to install.png>)

**Complete the Tera Term Setup Wizard**

The final step is to click on the **Finish** button to exit the setup wizard.

✅ Check the “Launch Tera Term” checkbox before you click \*\*Finish.\*\*

![launch-teraterm.png](<../../../.gitbook/assets/launch teraterm.png>)

### Configure Tera Term

ℹ️ When the emulator is configured, you can use it to set up your Modbus base unit(s).

Upon completion of the installation (and selection of the "Launch Tera Term" checkbox), the terminal application will launch and display the following dialog, starting the configuration process.

💡 If this dialog doesn't open when you start TeraTerm, you can get here by going to \*\*File > New connection\*\*.

![tera-term-new-connection.png](<../../../.gitbook/assets/tera term new connection.png>)

Click the **Serial** radio button to select the serial port you want to open, as seen in the following image, and then select the COM port from the drop-down menu.

✅ To configure the Modbus unit, you must select the USB Serial Port.

![tera-term-com-port.png](<../../../.gitbook/assets/tera term com port.png>)

This will open the Serial Port Setup dialog (see image below) with a variety of serial port settings. You can leave these default settings or change them to suit your application, and then click **OK** to save these settings.

📔 TeraTerm defaults to setting the baud rate at 9600 bps (8-N-1).

![tera-term-port-setup.png](<../../../.gitbook/assets/tera term port setup.png>)

Once you have clicked **OK**, this dialog will close and the title of your Tera Term window should change from **Disconnected** to something like **COM##: 9600.**

![active-tera-term.png](<../../../.gitbook/assets/active tera term.png>)

You are now ready to begin configuring your Sensorbee Modbus unit(s).

ℹ️ Navigate to the \[Base Unit Configuration Software guide]\(https://www.notion.so/Modbus-Configuration-37622fa76fa545c39acac0280861304f?pvs=21) for a detailed guide on configuring your Modbus unit(s).
