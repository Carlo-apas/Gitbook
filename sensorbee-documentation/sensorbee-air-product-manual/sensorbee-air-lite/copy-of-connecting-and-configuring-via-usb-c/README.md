# Copy of Connecting & Configuring via USB-C

A serial monitor or terminal emulator may be employed for configuration of the Modbus unit through its USB-C interface. Refer to the terminal emulator installation guide for comprehensive instructions on Tera Term, the emulator of choice.

\
ℹ️\
Important Constraints in Modbus Configuration: When setting up the Modbus communication for the Baseunit, it's important to note the relationship between parity and stop bits. Specifically, if you choose to operate without a parity bit ('No Parity'), the configuration will require the use of 2 stop bits. Conversely, if you opt for including a parity bit (either 'Even' or 'Odd' parity), the system will automatically configure the number of stop bits to 1. This limitation is set by the Modbus library used by the firmware, but is also what the Modbus specification defines as outlined in Modbus Specification 2.5.1.

\
The following text outlines the procedures for configuring the Modbus base unit, beginning with an overview of the main menu and subsequently covering additional available menus as detailed below.

\
[Main Menu](../../sensorbee-air-pro-2/connecting-and-configuring-via-usb-c/main-menu.md)\
[Polling Interval Menu](polling-interval-menu.md)\
[Firmware Update Menu](../../sensorbee-air-pro-2/connecting-and-configuring-via-usb-c/firmware-update-menu.md)\
[System Settings Menu](../../sensorbee-air-pro-2/connecting-and-configuring-via-usb-c/system-settings-menu.md)\
[Modbus Settings Menu](modbus-settings-menu.md)\
[Reset Menu](../../sensorbee-air-pro-2/connecting-and-configuring-via-usb-c/reset-menu.md)

\
To test Modbus communication over the RS-485 interface with a PC, the following tool is a good option: 4Next Modbus Software. Additionally, you'll also need an RS-485 to USB converter.
