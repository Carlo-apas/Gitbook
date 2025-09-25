# Modbus Configuration

***

A serial monitor or terminal emulator may be employed for configuration of the Modbus unit through its USB-C interface. Refer to the [terminal emulator installation guide](https://www.notion.so/Terminal-Emulator-4789627615584663a3c178696a03e517?pvs=21) for comprehensive instructions on Tera Term, the emulator of choice.

ℹ️ \*\*Important Constraints in Modbus Configuration\*\*: When setting up the Modbus communication for the Baseunit, it's important to note the relationship between parity and stop bits. Specifically, if you choose to operate without a parity bit ('No Parity'), the configuration will require the use of 2 stop bits. Conversely, if you opt for including a parity bit (either 'Even' or 'Odd' parity), the system will automatically configure the number of stop bits to 1. This limitation is set by the Modbus library used by the firmware, but is also what the Modbus specification defines as outlined in \[Modbus Specification]\(https://modbus.org/docs/Modbus\_over\_serial\_line\_V1\_02.pdf) 2.5.1.

The following text outlines the procedures for configuring the Modbus base unit, beginning with an overview of the main menu and subsequently covering additional available menus as detailed below.

Main Menu

Polling Interval Menu

Firmware Update Menu

System Settings Menu

Modbus Settings Menu

Reset Menu

To test Modbus communication over the RS-485 interface with a PC, the following tool is a good option: [**4Next Modbus Software**](https://www.4next.eu/en/prodotto/modbus-software/). Additionally, you'll also need an RS-485 to USB converter.
