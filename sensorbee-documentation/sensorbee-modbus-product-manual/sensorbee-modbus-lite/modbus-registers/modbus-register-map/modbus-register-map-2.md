# Modbus Register Map 2

***

| Name                   | Address (16 bit) | Address (10 bit) | Type | Unit  | # Registers | Access     | Default Value |
| ---------------------- | ---------------- | ---------------- | ---- | ----- | ----------- | ---------- | ------------- |
| PM1.0                  | 0x0050           | 80               | f32  | µg/m³ | 2           | read       | NaN           |
| PM1.0 24 hour average  | 0x0052           | 82               | f32  | µg/m³ | 2           | read       | NaN           |
| PM2.5                  | 0x0054           | 84               | f32  | µg/m³ | 2           | read       | NaN           |
| PM2.5 24 hour average  | 0x0056           | 86               | f32  | µg/m³ | 2           | read       | NaN           |
| PM10.0                 | 0x0058           | 88               | f32  | µg/m³ | 2           | read       | NaN           |
| PM10.0 24 hour average | 0x005A           | 90               | f32  | µg/m³ | 2           | read       | NaN           |
| PM offset factor       | 0x005C           | 92               | f32  |       | 2           | read/write | 1             |
| PM offset constant     | 0x005E           | 94               | f32  |       | 2           | read/write | 0             |
| Clean interval         | 0x0060           | 96               | u16  | hours | 1           | read/write | 24            |
| Temperature            | 0x0080           | 128              | f32  | °C    | 2           | read       | NaN           |
| Temperature minimum    | 0x0082           | 130              | f32  | °C    | 2           | read       | NaN           |
| Temperature maximum    | 0x0084           | 132              | f32  | °C    | 2           | read       | NaN           |
| Humidity               | 0x0086           | 134              | f32  | % RH  | 2           | read       | NaN           |
| Humidity minimum       | 0x0088           | 136              | f32  | % RH  | 2           | read       | NaN           |
| Humidity maximum       | 0x008A           | 138              | f32  | % RH  | 2           | read       | NaN           |
| Pressure               | 0x008C           | 140              | f32  | Pa    | 2           | read       | NaN           |
| Pressure minimum       | 0x008E           | 142              | f32  | Pa    | 2           | read       | NaN           |
| Pressure maximum       | 0x0090           | 144              | f32  | Pa    | 2           | read       | NaN           |
| Dew point              | 0x0092           | 146              | f32  | °C    | 2           | read       | NaN           |
| Noise                  | 0x0094           | 148              | f32  | dbA   | 2           | read       | NaN           |

***

**v2.10.3**

| VOC                    | 0x0061 | 97   | u16 |       | 1 | read       | 0   |
| ---------------------- | ------ | ---- | --- | ----- | - | ---------- | --- |
| NOX                    | 0x0062 | 98   | u16 |       | 1 | read       | 0   |
| PM4.0                  | 0x0063 | 99   | f32 | µg/m³ | 2 | read       | 0   |
| PM4.0 24 hour average  | 0x0065 | 101  | f32 | µg/m³ | 2 | read       | 0   |
| PC1.0                  | 0x0067 | 103  | u32 |       | 2 | read       | 0   |
| PC1.0 24 hour average  | 0x0069 | 105  | f32 |       | 2 | read       | 0   |
| PC2.5                  | 0x006B | 107  | u32 |       | 2 | read       | 0   |
| PC2.5 24 hour average  | 0x006D | 109  | f32 |       | 2 | read       | 0   |
| PC4.0                  | 0x006F | 111  | u32 |       | 2 | read       | 0   |
| PC4.0 24 hour average  | 0x0071 | 113  | f32 |       | 2 | read       | 0   |
| PC10.0                 | 0x0073 | 115  | u32 |       | 2 | read       | 0   |
| PC10.0 24 hour average | 0x0075 | 117  | f32 |       | 2 | read       | 0   |
| PM1.0 Slope            | 0x0400 | 1024 | f32 |       | 2 | read/write | 1.0 |
| PM1.0 Offset           | 0x0402 | 1026 | f32 |       | 2 | read/write | 0.0 |
| PM2.5 Slope            | 0x0404 | 1028 | f32 |       | 2 | read/write | 1.0 |
| PM2.5 Offset           | 0x0406 | 1030 | f32 |       | 2 | read/write | 0.0 |
| PM10.0 Slope           | 0x0408 | 1032 | f32 |       | 2 | read/write | 1.0 |
| PM10.0 Offset          | 0x040A | 1034 | f32 |       | 2 | read/write | 0.0 |

### PM1.0 24 hour average (Address = 0x0052)

| Address (16 bit) | Address (10 bit) | Type | Unit  | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0050           | 80               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the PM1.0 retrieved from the most recent poll.

### PM1.0 24 hour average (Address = 0x0052)

| Address (16 bit) | Address (10 bit) | Type | Unit  | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0052           | 82               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the 24 hour average PM1.0 retrieved from the most recent poll.

### PM2.5 (Address = 0x0054)

| Address (16 bit) | Address (10 bit) | Type | Unit  | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0054           | 84               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the PM2.5 retrieved from the most recent poll.

### PM2.5 24 hour average (Address = 0x0056)

| Address (16 bit) | Address (10 bit) | Type | Unit  | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0056           | 86               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the 24 hour average PM2.5 retrieved from the most recent poll.

### PM10.0 (Address = 0x0058)

| Address (16 bit) | Address (10 bit) | Type | Unit  | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0058           | 88               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the PM10.0 retrieved from the most recent poll.

### PM10.0 24 hour average (Address = 0x005A)

| Address (16 bit) | Address (10 bit) | Type | Unit  | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x005A           | 90               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the 24 hour average PM10.0 retrieved from the most recent poll.

### PM offset factor (Address = 0x005C)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access     | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x005C           | 92               | f32  |      | 2           | read/write | 1             |

This register contains the offset factor for PM sensor.

### PM offset constant (Address = 0x005E)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access     | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x005E           | 94               | f32  |      | 2           | read/write | 0             |

This register contains the offset constant for PM sensor.

### Clean interval (Address = 0x0060)

| Address (16 bit) | Address (10 bit) | Type | Unit  | # Registers | Access     | Default Value |
| ---------------- | ---------------- | ---- | ----- | ----------- | ---------- | ------------- |
| 0x0060           | 96               | u16  | hours | 1           | read/write | 24            |

This register contains the interval time for clean the sensor in hours.

### Temperature (Address = 0x0080)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0080           | 128              | f32  | °C   | 2           | read   | NaN           |

This register contains the temperature retrieved from the most recent poll.

### Temperature minimum (Address = 0x0082)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0082           | 130              | f32  | °C   | 2           | read   | NaN           |

This register contains the minimum temperature since the reset or boot.

### Temperature maximum (Address = 0x0084)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0084           | 132              | f32  | °C   | 2           | read   | NaN           |

This register contains the maximum temperature since the reset or boot.

### Humidity (Address = 0x0086)

\| Address (16 bit)

I apologize, it seems like the previous message was cut off. Please let me know what you would like me to continue writing.

### Humidity (Address = 0x0086)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0086           | 134              | f32  | % RH | 2           | read   | NaN           |

This register contains the humidity retrieved from the most recent poll.

### Humidity minimum (Address = 0x0088)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0088           | 136              | f32  | % RH | 2           | read   | NaN           |

This register contains the minimum humidity since the reset or boot.

### Humidity maximum (Address = 0x008A)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x008A           | 138              | f32  | % RH | 2           | read   | NaN           |

This register contains the maximum humidity since the reset or boot.

### Pressure (Address = 0x008C)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x008C           | 140              | f32  | Pa   | 2           | read   | NaN           |

This register contains the pressure retrieved from the most recent poll.

### Pressure minimum (Address = 0x008E)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value | Notes                        |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- | ---------------------------- |
| 0x008E           | 142              | f32  | Pa   | 2           | read   | NaN           | From reset data time or boot |

This register contains the minimum pressure since the reset or boot.

### Pressure maximum (Address = 0x0090)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value | Notes                        |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- | ---------------------------- |
| 0x0090           | 144              | f32  | Pa   | 2           | read   | NaN           | From reset data time or boot |

This register contains the maximum pressure since the reset or boot.

### Dew point (Address = 0x0092)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0092           | 146              | f32  | °C   | 2           | read   | NaN           |

This register contains the dew point calculated from the most recent poll.

### Noise (Address = 0x0094)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0094           | 148              | f32  | dbA  | 2           | read   | NaN           |

This register contains the noise level retrieved from the most recent poll.

### PM4.0 (Address = 0x0063)

| Address (16 bit) | Address (10 bit) | Type | Unit  | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0063           | 99               | f32  | µg/m³ | 2           | read   | 0.0           |

This register contains the PM4.0 value retrieved from the most recent poll.

### PM4.0 24 hour average (Address = 0x0065)

| Address (16 bit) | Address (10 bit) | Type | Unit  | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0065           | 101              | f32  | µg/m³ | 2           | read   | 0.0           |

This register contains the 24 hour average PM4.0 retrieved from the most recent poll.

### PC1.0 (Address = 0x0067)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0067           | 103              | u32  |      | 2           | read   | 0             |

This register contains the most recent PC1.0 (Particle Count 1.0) value.

### PC1.0 24 hour average (Address = 0x0069)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0069           | 105              | f32  |      | 2           | read   | 0.0           |

This register contains the most recent PC1.0 24 hour average value.

### PC2.5 (Address = 0x006B)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x006B           | 107              | u32  |      | 2           | read   | 0             |

This register contains the most recent PC2.5 (Particle Count 2.5) value.

### PC2.5 24 hour average (Address = 0x006D)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x006D           | 109              | f32  |      | 2           | read   | 0.0           |

This register contains the most recent PC2.5 24 hour average value.

***

### PC4.0 (Address = 0x006F)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x006F           | 111              | u32  |      | 2           | read   | 0             |

This register contains the most recent PC4.0 (Particle Count 4.0) value.

### PC4.0 24 hour average (Address = 0x0071)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0071           | 113              | f32  |      | 2           | read   | 0.0           |

This register contains the most recent PC4.0 24 hour average value.

***

### PC10.0 (Address = 0x0073)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0073           | 115              | u32  |      | 2           | read   | 0             |

This register contains the most recent PC10.0 (Particle Count 10.0) value.

### PC10.0 24 hour average (Address = 0x0075)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x0075           | 117              | f32  |      | 2           | read   | 0.0           |

This register contains the most recent PC10.0 24 hour average value.

### PM1.0 Slope (Address = 0x0400)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access     | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x0400           | 1024             | f32  |      | 2           | Read/Write | 1.0           |

This register contains the slope value (k) used in the linear transformation function (kx + m) for calculating the PM1.0 (Particulate Matter 1.0) value.

### PM1.0 Offset (Address = 0x0402)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access     | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x0402           | 1026             | f32  |      | 2           | Read/Write | 0.0           |

This register contains the offset value (m) used in the linear transformation function (kx + m) for calculating the PM1.0 (Particulate Matter 1.0) value.

### PM2.5 Slope (Address = 0x0404)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access     | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x0404           | 1028             | f32  | -    | 2           | Read/Write | 1.0           |

This register contains the slope value (k) used in the linear transformation function (kx + m) for calculating the PM2.5 (Particulate Matter 2.5) value.

### PM2.5 Offset (Address = 0x0406)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access     | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x0406           | 1030             | f32  | -    | 2           | Read/Write | 0.0           |

This register contains the offset value (m) used in the linear transformation function (kx + m) for calculating the PM2.5 (Particulate Matter 2.5) value.

### PM10.0 Slope (Address = 0x0408)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access     | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x0408           | 1032             | f32  | -    | 2           | Read/Write | 1.0           |

This register contains the slope value (k) used in the linear transformation function (kx + m) for calculating the PM10.0 (Particulate Matter 10.0) value.

### PM10.0 Offset (Address = 0x040A)

| Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access     | Default Value |
| ---------------- | ---------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x040A           | 1034             | f32  | -    | 2           | Read/Write | 0.0           |

This register contains the offset value (m) used in the linear transformation function (kx + m) for calculating the PM10.0 (Particulate Matter 10.0) value.
