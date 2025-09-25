# Modbus Registers

***

### Configuring the Base Unit’s Registers

Multiple simple registers are used to configure the base unit.

📔 Most of these configurations will be done using the configuration interface. However, it is possible only to use Modbus to configure the unit.

The parameters in this register are read/write and can be modified by writing to them during the [initial configuration process](https://www.notion.so/Modbus-Configuration-37622fa76fa545c39acac0280861304f?pvs=21). Once this configuration is operational, it will be stored in the device’s non-volatile memory and become the device’s default configuration

💡 This register data is represented as a 16-bit unsigned integer.

### The Sensorbee Modbus’s Default Configuration Parameters

The following table describes the Sensorbee Modbus’s default configuration parameters with their value ranges.

| Parameter     | Address | Address (Hex) | Value                 | Version |
| ------------- | ------- | ------------- | --------------------- | ------- |
| Slave Address | 0       | 0x0000        | Value range: 1 to 247 |         |
| Default: 1.   | ≥ 1.0.0 |               |                       |         |
| Baud rate     | 8       | 0x0008        | Value range:          |         |

1. 9600
2. 115200
3. 192000
4. 576000

Default: 9600. | ≥ 1.0.0 | | Parity | 38 | 0x0026 | Value range: 0: None 1: Odd 2: Even

Default: 0 | ≥ 2.0.0 | | Stop Bits | 39 | 0x0027 | Value range: 1: 1 stop bit 2: 2 stop bits

Default: 2 | ≥ 2.0.0 |

⚠️ While the register can accept any 32-bit value, the Modbus protocol only accepts specific values. As a result, it is crucial to be mindful of the possibility of configuring an invalid value.

### The Sensorbee Modbus’s Measurement Register

The Sensorbee Modbus unit stores its sensor measurement values in the Modbus input register.

💡 See the following register map for details on the data we collect from the sensors attached to the unit

