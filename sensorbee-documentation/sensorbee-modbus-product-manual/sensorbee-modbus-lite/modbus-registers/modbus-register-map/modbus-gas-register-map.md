# Modbus Gas Register Map

***

This document provides a register map for all the gas related registers in the Modbus Base Unit. The map includes information on the various registers used to store gas concentration data, as well as calibration and sensitivity values. In addition to the register map, this document provides a brief introduction to the gas sensor and its capabilities.

## Data Registers

## Note on Gas Sensitivity

⚠️ It is generally not advisable to directly adjust the sensitivity of gas sensors. Instead, it is recommended to use gas calibration or the offset factor and constant registers to fine-tune the gas sensor data.

***

| Name                  | Address (16 bit) | Address (10 bit) | Type | Unit   | # Registers | Access     | Default Value |
| --------------------- | ---------------- | ---------------- | ---- | ------ | ----------- | ---------- | ------------- |
| CO₂                   | 0x00A0           | 160              | f32  | ppm    | 2           | read       | NaN           |
| CO₂ 1 hour average    | 0x00A2           | 162              | f32  | ppm    | 2           | read       | NaN           |
| CO₂ offset factor     | 0x00A4           | 164              | f32  |        | 2           | read/write | 1             |
| CO₂ offset constant   | 0x00A6           | 166              | f32  |        | 2           | read/write | 0             |
| NO₂                   | 0x00C0           | 192              | f32  | µg/m³  | 2           | read       | NaN           |
| NO₂ 1 hour average    | 0x00C2           | 194              | f32  | µg/m³  | 2           | read       | NaN           |
| NO₂ offset factor     | 0x00C4           | 196              | f32  |        | 2           | read/write | 1             |
| NO₂ offset constant   | 0x00C6           | 198              | f32  |        | 2           | read/write | 0             |
| NO₂ ce current offset | 0x00C8           | 200              | f32  |        | 2           | read/write | 0             |
| NO₂ sensitivity       | 0x00CA           | 202              | f32  | nA/ppm | 2           | read/write | 123           |
| CO                    | 0x00E0           | 224              | f32  | mg/m³  | 2           | read       | NaN           |
| CO 8 hour average     | 0x00E2           | 226              | f32  | mg/m³  | 2           | read       | NaN           |
| CO offset factor      | 0x00E4           | 228              | f32  |        | 2           | read/write | 1             |
| CO offset constant    | 0x00E6           | 230              | f32  |        | 2           | read/write | 0             |
| CO current offset     | 0x00E8           | 232              | f32  |        | 2           | read/write | 0             |
| CO sensitivity        | 0x00EA           | 234              | f32  | nA/ppm | 2           | read/write | 123           |
| O₃                    | 0x0100           | 256              | f32  | µg/m³  | 2           | read       | NaN           |
| O₃ 1 hour average     | 0x0102           | 258              | f32  | µg/m³  | 2           | read       | NaN           |
| O₃ 8 hour average     | 0x0104           | 260              | f32  | µg/m³  | 2           | read       | NaN           |
| O₃ offset factor      | 0x0106           | 262              | f32  |        | 2           | read/write | 1             |
| O₃ offset constant    | 0x0108           | 264              | f32  |        | 2           | read/write | 0             |
| O₃ sensitivity        | 0x010A           | 266              | f32  |        | 2           | read/write | 123           |
| O₃ NO₂ sensitivity    | 0x010C           | 268              | f32  |        | 2           | read/write | 123           |
| SO₂                   | 0x0120           | 288              | f32  | µg/m³  | 2           | read       | NaN           |
| SO₂ 1 hour average    | 0x0122           | 290              | f32  | µg/m³  | 2           | read       | NaN           |
| SO₂ 24 hour average   | 0x0124           | 292              | f32  | µg/m³  | 2           | read       | NaN           |
| SO₂ offset factor     | 0x0126           | 294              | f32  |        | 2           | read/write | 1             |
| SO₂ offset constant   | 0x0128           | 296              | f32  |        | 2           | read/write | 0             |
| SO₂ sensitivity       | 0x012A           | 298              | f32  | nA/ppm | 2           | read/write | 123           |
| NO                    | 0x01A0           | 416              | f32  | µg/m³  | 2           | read       | NaN           |
| NO 1 hour average     | 0x01A2           | 418              | f32  | µg/m³  | 2           | read       | NaN           |
| NO offset factor      | 0x01A4           | 420              | f32  |        | 2           | read/write | 1             |
| NO offset constant    | 0x01A6           | 422              | f32  |        | 2           | read/write | 0             |
| NO sensitivity        | 0x01A8           | 424              | f32  | nA/ppm | 2           | read/write | 123           |

## CO₂ (Address = 0x00A0)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x00A0                | 160               | f32  | ppm  | 2           | read   | NaN           |

This register contains the CO₂ value retrieved from the most recent poll.

## CO₂ 1 hour average (Address = 0x00A2)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ------ | ------------- |
| 0x00A2                | 162               | f32  | ppm  | 2           | read   | NaN           |

This register contains the 1-hour average CO₂ value.

## CO₂ offset factor (Address = 0x00A4)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x00A4                | 164               | f32  |      | 2           | read/write | 1             |

This register represents the CO₂ offset factor.

## CO₂ offset constant (Address = 0x00A6)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x00A6                | 166               | f32  |      | 2           | read/write | 0             |

This register represents the CO₂ offset constant.

## NO₂ (Address = 0x00C0)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x00C0                | 192               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the NO₂ value retrieved from the most recent poll.

## NO₂ 1 hour average (Address = 0x00C2)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x00C2                | 194               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the 1-hour average NO₂ value.

## NO₂ offset factor (Address = 0x00C4)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x00C4                | 196               | f32  |      | 2           | read/write | 1             |

This register represents the NO₂ offset factor.

## NO₂ offset constant (Address = 0x00C6)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x00C6                | 198               | f32  |      | 2           | read/write | 0             |

This register represents the NO₂ offset constant.

## NO₂ ce current offset (Address = 0x00C8)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x00C8                | 200               | f32  |      | 2           | read/write | 0             |

This register represents the NO₂ ce current offset.

## NO₂ sensitivity (Address = 0x00CA)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit   | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ------ | ----------- | ---------- | ------------- |
| 0x00CA                | 202               | f32  | nA/ppm | 2           | read/write | 0             |

This register represents the sensitivity of NO₂.

## CO (Address = 0x00E0)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x00E0                | 224               | f32  | mg/m³ | 2           | read   | NaN           |

This register contains the CO value retrieved from the most recent poll.

## CO 8 hour average (Address = 0x00E2)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x00E2                | 226               | f32  | mg/m³ | 2           | read   | NaN           |

This register contains the 8-hour average CO value.

## CO offset factor (Address = 0x00E4)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x00E4                | 228               | f32  |      | 2           | read/write | 1             |

This register represents the CO offset factor.

## CO offset constant (Address = 0x00E6)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x00E6                | 230               | f32  |      | 2           | read/write | 0             |

This register represents the CO offset constant.

## CO current offset (Address = 0x00E8)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x00E8                | 232               | f32  |      | 2           | read/write | 0             |

This register represents the CO current offset.

## CO sensitivity (Address = 0x00EA)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit   | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ------ | ----------- | ---------- | ------------- |
| 0x00EA                | 234               | f32  | nA/ppm | 2           | read/write | 0             |

This register represents the sensitivity of CO.

## O₃ (Address = 0x0100)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0100                | 256               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the O₃ value retrieved from the most recent poll.

## O₃ 1 hour average (Address = 0x0102)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0102                | 258               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the 1-hour average O₃ value.

## O₃ 8 hour average (Address = 0x0104)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0104                | 260               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the 8-hour average O₃ value.

## O₃ offset factor (Address = 0x0106)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x0106                | 262               | f32  |      | 2           | read/write | 1             |

This register represents the O₃ offset factor.

## O₃ offset constant (Address = 0x0108)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x0108                | 264               | f32  |      | 2           | read/write | 0             |

This register represents the O₃ offset constant.

## O₃ sensitivity (Address = 0x010A)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x010A                | 266               | f32  |      | 2           | read/write | 0             |

This register represents the sensitivity of O₃.

## O₃ NO₂ sensitivity (Address = 0x010C)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x010C                | 268               | f32  |      | 2           | read/write | 0             |

This record shows the sensitivity of the O₃ sensor to NO₂. Since the O₃ sensor is sensitive to both NO₂ and O₃, we need a separate sensitivity value for each gas.

## SO₂ (Address = 0x0120)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0120                | 288               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the SO₂ value retrieved from the most recent poll.

## SO₂ 1 hour average (Address = 0x0122)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0122                | 290               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the 1-hour average SO₂ value.

## SO₂ 24 hour average (Address = 0x0124)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x0124                | 292               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the 24-hour average SO₂ value.

## SO₂ offset factor (Address = 0x0126)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x0126                | 294               | f32  |      | 2           | read/write | 1             |

This register represents the SO₂ offset factor.

## SO₂ offset constant (Address = 0x0128)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x0128                | 296               | f32  |      | 2           | read/write | 0             |

This register represents the SO₂ offset constant.

## SO₂ sensitivity (Address = 0x012A)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit   | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ------ | ----------- | ---------- | ------------- |
| 0x012A                | 298               | f32  | nA/ppm | 2           | read/write | 0             |

This register represents the sensitivity of SO₂.

## NO (Address = 0x01A0)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x01A0                | 416               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the NO value retrieved from the most recent poll.

## NO 1 hour average (Address = 0x01A2)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit  | # Registers | Access | Default Value |
| --------------------- | ----------------- | ---- | ----- | ----------- | ------ | ------------- |
| 0x01A2                | 418               | f32  | µg/m³ | 2           | read   | NaN           |

This register contains the 1-hour average NO value.

## NO offset factor (Address = 0x01A4)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x01A4                | 420               | f32  |      | 2           | read/write | 1             |

This register represents the NO offset factor.

## NO offset constant (Address = 0x01A6)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ---- | ----------- | ---------- | ------------- |
| 0x01A6                | 422               | f32  |      | 2           | read/write | 0             |

This register represents the NO offset constant.

## NO sensitivity (Address = 0x01A8)

| Address (Hexadecimal) | Address (Decimal) | Type | Unit   | # Registers | Access     | Default Value |
| --------------------- | ----------------- | ---- | ------ | ----------- | ---------- | ------------- |
| 0x01A8                | 424               | f32  | nA/ppm | 2           | read/write | 0             |

This register represents the sensitivity of NO.
