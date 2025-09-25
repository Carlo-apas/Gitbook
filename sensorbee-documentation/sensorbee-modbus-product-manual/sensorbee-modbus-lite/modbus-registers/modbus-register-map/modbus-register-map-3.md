# Modbus Register Map 3

### (Not Supported Yet)

| Name                         | Address (16 bit) | Address (10 bit) | Type | Unit | # Registers | Access     | Default Value |
| ---------------------------- | ---------------- | ---------------- | ---- | ---- | ----------- | ---------- | ------------- |
| Rain                         | 0x01C0           | 448              | f32  | mm   | 2           | read       | NaN           |
| Rain minimum                 | 0x01C2           | 450              | f32  | mm   | 2           | read       | NaN           |
| Rain maximum                 | 0x01C4           | 452              | f32  | mm   | 2           | read       | NaN           |
| Rain offset factor           | 0x01C6           | 454              | f32  |      | 2           | read/write | 1             |
| Rain offset constant         | 0x01C8           | 456              | f32  |      | 2           | read/write | 0             |
| Wind angle                   | 0x01E0           | 480              | f32  | °    | 2           | read       | NaN           |
| Wind angle average in period | 0x01E2           | 482              | f32  | °    | 2           | read       | NaN           |
| Wind speed                   | 0x01E4           | 484              | f32  | dkt  | 2           | read       | NaN           |
| Wind speed average in period | 0x01E6           | 486              | f32  | dkt  | 2           | read       | NaN           |
| Wind speed maximum           | 0x01E8           | 488              | f32  | dkt  | 2           | read       | NaN           |
| Wind offset factor           | 0x01EA           | 490              | f32  |      | 2           | read/write | 1             |
| Wind offset constant         | 0x01EC           | 492              | f32  |      | 2           | read/write | 0             |
| Wind sample period           | 0x01EE           | 494              | u8   |      |             |            |               |

0: \~1.6 seconds 1: \~14 seconds | | 2 | read/write | 0 | | Tag firmware version | 0x(0-F)300 | 768 + (4096 \* X) | Firmware Version | | 2 | read | 0 | | Tag serial number | 0x(0-F)302 | 770 + (4096 \* X) | u16 | | 1 | read | 0 | | Tag family | 0x(0-F)303 | 771 + (4096 \* X) | u16 | | 1 | read | 0 | | Tag always on | 0x(0-F)304 | 772 + (4096 \* X) | bool | | 1 | read/write | false | | Tag preheat time | 0x(0-F)305 | 773 + (4096 \* X) | u32 | ms | 2 | read/write | 10000 | | Temperature | 0x(0-F)800 | 2048 + (4096 \* X) | f32 | °C | 2 | read | NaN | | Temperature minimum | 0x(0-F)802 | 2050 + (4096 \* X) | f32 | °C | 2 | read | NaN | | Temperature maximum | 0x(0-F)804 | 2052 + (4096 \* X) | f32 | °C | 2 | read | NaN | | Temperature offset factor | 0x(0-F)806 | 2054 + (4096 \* X) | f32 | | 2 | read/write | 1 | | Temperature offset constant | 0x(0-F)808 | 2056 + (4096 \* X) | f32 | | 2 | read/write | 0 | | Humidity | 0x(0-F)A00 | 2560 + (4096 \* X) | f32 | % RH | 2 | read | NaN | | Humidity minimum | 0x(0-F)A02 | 2562 + (4096 \* X) | f32 | % RH | 2 | read | NaN | | Humidity maximum | 0x(0-F)A04 | 2564 + (4096 \* X) | f32 | % RH | 2 | read | NaN | | Humidity offset factor | 0x(0-F)A06 | 2566 + (4096 \* X) | f32 | | 2 | read/write | 1 | | Humidity offset constant | 0x(0-F)A08 | 2568 + (4096 \* X) | f32 | | 2 | read/write | 0 | | Pressure | 0x(0-F)C00 | 3072 + (4096 \* X) | f32 | hPa | 2 | read | NaN | | Pressure minimum | 0x(0-F)C02 | 3074 + (4096 \* X) | f32 | hPa | 2 | read | NaN | | Pressure maximum | 0x(0-F)C04 | 3076 + (4096 \* X) | f32 | hPa | 2 | read | NaN | | Pressure offset factor | 0x(0-F)C06 | 3078 + (4096 \* X) | f32 | | 2 | read/write | 1 | | Pressure offset constant | 0x(0-F)C08 | 3080 + (4096 \* X) | f32 | | 2 | read/write | 0 |
