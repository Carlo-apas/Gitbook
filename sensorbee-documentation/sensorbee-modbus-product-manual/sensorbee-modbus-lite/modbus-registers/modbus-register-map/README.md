# Modbus Register Map

## Modbus Register Map

## General Modbus Registers

In this chapter, we will cover the initial section of the modbus register map. We explore the different types of registers and their corresponding functions, as well as the various data types and their representations within the modbus protocol.

### Glossary

* u8: 8-bit unsigned integer.
* u16: 16-bit unsigned integer.
* u32: 32-bit unsigned integer.
* f32: IEEE 754 single-precision floating-point value.
* string: A null-terminated string of ASCII characters.
* read: Modbus input register.
* read/write: Modbus holding register.

### Register List

| Name                               | Address (Hexadecimal) | Address (Decimal) | Type   | Unit | # Registers | Access     |
| ---------------------------------- | --------------------- | ----------------- | ------ | ---- | ----------- | ---------- |
| Modbus Address                     | 0x0000                | 0                 | u8     |      | 1           | read/write |
| Base Unit SKU                      | 0x0001                | 1                 | u32    |      | 2           | read       |
| Supplier Name                      | 0x0003                | 3                 | string |      | 5           | read       |
| Modbus UART Baud Rate              | 0x0008                | 8                 | u32    |      | 2           | read/write |
| Base Unit Hardware Version         | 0x000A                | 10                | string |      | 2           | read       |
| Base Unit Firmware Version         | 0x000C                | 12                | string |      | 6           | read       |
| Base Unit Serial Number            | 0x0012                | 18                | u32    |      | 2           | read       |
| Polling Interval                   | 0x0014                | 20                | u32    | secs | 2           | read/write |
| ≥ 0 - Polling interval in seconds. |                       |                   |        |      |             |            |
| No. of Tags                        | 0x0016                | 22                | u8     |      | 1           | read       |
| Status                             | 0x0017                | 23                | u16    |      | 1           | read       |
| Device Name                        | 0x0018                | 24                | string |      | 4           | read/write |
| Reset Data                         | 0x001C                | 28                |        |      | 1           | write      |
| Enable Licences                    | 0x001D                | 29                |        |      |             | write      |

**≥ 2.0.0 ————————————————————————————————————————**

| Modbus Parity    | 0x0026 | 38 | u8 |   | 1 | read/write |
| ---------------- | ------ | -- | -- | - | - | ---------- |
| Modbus Stop Bits | 0x0027 | 39 | u8 |   | 1 | read/write |

#### Modbus Address (Address = 0)

| Address (16 bit) | Address (10 bit) | Type | # Registers | Access     | Default Value |
| ---------------- | ---------------- | ---- | ----------- | ---------- | ------------- |
| 0x0000           | 0                | u8   | 1           | read/write | 0x01          |

The Modbus Address register is used to set or get the slave address over the Modbus protocol.

#### Base Unit SKU (Address = 0x0001)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0001                | 1                 | u32  |      | 2           | read   |               |

The Base Unit SKU register holds the Stock Keeping Unit (SKU) of the base unit.

#### Supplier Name (Address = 0x0003)

| Address (Hexadecimal) | Address (Decimal) | Type         | Unit | # Registers | Access | Default Value |
| --------------------- | ----------------- | ------------ | ---- | ----------- | ------ | ------------- |
| 0x0003                | 3                 | ASCII String |      | 5           | read   | Sensorbee     |

The Supplier Name register is used to store the name of the supplier of the base unit. It is a null terminated ASCII string.

#### Modbus UART Baud Rate (Address = 0x0008)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x0008                | 8                 | u32  |      | 2           | read/write | 9600          |

The Modbus UART Baud Rate register is used to set or get the baud rate of the Modbus UART communication.

#### Base Unit Hardware Version (Address = 0x000A)

| Address (Hexadecimal) | Address (Decimal) | Type             | Unit | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---------------- | ---- | ----------- | ------ | ------------- |
| 0x000A                | 10                | Firmware Version |      | 2           | read   | 0             |

The Base Unit Hardware Version register holds the firmware version of the base unit.

#### Base Unit Hardware Version (Address = 0x000C)

| Address (Hexadecimal) | Address (Decimal) | Type   | Unit | # Registers | Access | Default Value |
| --------------------- | ----------------- | ------ | ---- | ----------- | ------ | ------------- |
| 0x000C                | 12                | string |      | 6           | read   |               |

The Base Unit Firmware Version register holds the hardware version of the base unit. It is a null terminated string.

#### Base Unit Serial Number (Address = 0x0012)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0012                | 18                | u32  |      | 2           | read   | 0             |

The Base Unit Serial Number register holds the serial number of the base unit.

#### Polling Interval (Address = 0x0014)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x0014                | 20                | u32  | secs | 2           | read/write | 5             |

The Polling Interval register is used to set or get the time interval between data collections. A value of 0 indicates manual mode and data can be collected whenever required.

⚠️ Manual mode is currently not supported yet.

#### No. of Tags (Address = 0x0016)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0016                | 22                | u8   |      | 1           | read   | 0             |

The No. of Tags register holds the number of tags in the base unit.

#### Status (Address = 0x0017)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0017                | 23                | u16  |      | 1           | read   | 0             |

The Status register holds the status of the base unit.

#### Device Name (Address = 0x0018)

| Address (Hexadecimal) | Address (Decimal) | Type   | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ------ | ---- | ----------- | ---------- | ------------- |
| 0x0018                | 24                | string |      | 4           | read/write |               |

The Device Name register holds the name of the device. The string is null-terminated unless all registers are used to store the string.

#### Reset Data (Address = 0x001C)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x001C                | 28                | Any  |      | 1           | write  |               |

The Reset Data register is used to reset the maximum and minimum statistics for data collected during polling.

#### Enable Licences (Address = 0x001D)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x001D                | 29                | u8   |      | 1           | read/write | 0: None       |

This register is used to enable the license for the noise sensor.

#### Modbus Parity (Address = 0x0026) (≥ 2.0.0)

This register can be used to control the parity configuration of the Modbus serial interface. The register can be configured to the following values:

* **0:** None
* **1:** Odd
* **2:** Even

⚠️ After setting the value in this register, a reboot must take place for the change to take effect.

#### Modbus Stop Bits (Address = 0x0027) (≥ 2.0.0)

This register can be used to set or get the stop bit configuration of the Modbus serial interface. The register can be configured to the following values:

* **1:** 1 stop bit
* **2:** 2 stop bits

⚠️ After setting the value in this register, a reboot must take place for the change to take effect.

### Additional Information

For detailed information about additional Modbus registers, please refer to:

Modbus Register Map 2

Modbus Register Map 3

Modbus Gas Register Map
