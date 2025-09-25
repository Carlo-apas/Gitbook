# STATUS LED

#### Sensorbee Air Cellular Lite and Pro <a href="#a7712421b3864008a2497d3a22d3b0db" id="a7712421b3864008a2497d3a22d3b0db"></a>

The status LED, visible from the outside and located at the top-right corner of the unit's base, serves to indicate the current status as well as any potential errors.

<figure><img src="https://image-forwarder.notaku.so/aHR0cHM6Ly93d3cubm90aW9uLnNvL2ltYWdlL2h0dHBzJTNBJTJGJTJGcHJvZC1maWxlcy1zZWN1cmUuczMudXMtd2VzdC0yLmFtYXpvbmF3cy5jb20lMkY4YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTclMkZiOTAwOTk3Mi05ODZiLTQ2ZWYtOTczYy1iYjNkNGE3YTQxMWQlMkZVbnRpdGxlZC5wbmc_dGFibGU9YmxvY2smc3BhY2VJZD04YTlhZWQwNi1mODQ0LTRkZTQtYjk2Yi1jMTUyNjkzMWM1NTcmaWQ9YjUwMDg2NWItODQzNC00MDBkLWFhZGUtM2NhYzA0MzM0M2ZjJmNhY2hlPXYyJndpZHRoPTEwNzA=" alt="Image without caption"><figcaption></figcaption></figure>

#### General LED Status <a href="#id-499b887f056e447d8362da3e5a2bc956" id="id-499b887f056e447d8362da3e5a2bc956"></a>

The following table contains the general color codes that are used by the device.

| Color                   | State                  | Short Description              | Description                                                                                                                                               |
| ----------------------- | ---------------------- | ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Green                   | Solid                  | Booting                        | When the device starts, the LED will be solid green until it begins connecting to the network.                                                            |
| Blue                    | Solid                  | Connecting to network          | When the LED is blue, the device is attempting to connect to the network. The LED will turn off once connected.                                           |
| Green                   | Blink once             | Registered to the LwM2M server | After connecting to the network, the LED will blink green for 1 second to indicate successful registration to the LwM2M server.                           |
| Green                   | Blink 5 times          | Device is rebooting            | If the LED blinks 5 times, the device is rebooting.                                                                                                       |
| Purple                  | Blink                  | Connecting to bootstrap server | The LED blinks purple when the device is trying to connect to the bootstrap server.                                                                       |
| Purple                  | Solid                  | Bootstrap complete             | Once the bootstrap process is complete, the LED turns solid purple. The device will then try t to connect to the server provided by the bootstrap server. |
| Red                     | Solid                  | An error has occurred          | An error has occurred during boot up or when trying to connect to the server.                                                                             |
| White (Very Light Blue) | Solid                  | Device is in menu mode         | The device is currently in menu mode and will not run its normal program until the USB cable is disconnected and the device is restarted.                 |
| Red                     | Blink every 10 seconds | Device is in deep sleep        | The device is currently in deep sleep waiting for the battery to be recharged to a certain threshold.                                                     |

#### LED Status During Shutdown <a href="#id-73e3f0ea4e514a5e951494e371a72d7e" id="id-73e3f0ea4e514a5e951494e371a72d7e"></a>

The following table will describe the LED status when powering off the device.

| Color | State | Short Description                | Description                                                                                                                                                                                    |
| ----- | ----- | -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Red   | Solid | Device is powering down.         | The device is currently powering down itself. When completed the LED will be turned off.                                                                                                       |
| Green | Blink | The powering down process failed | If the device starts to blink green after the powering down process has started, this indicates the powering down failed. This is because the external power is still connected to the device. |

#### LED Status During Menu Mode <a href="#id-3a971697a9484501b66905419a4989c2" id="id-3a971697a9484501b66905419a4989c2"></a>

| Color        | State | Short Description                    | Description                                                                                                                                                      |
| ------------ | ----- | ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| _Light Blue_ | Blink | New firmware is being transferred    | When the LED is blinking in a light blue color, it is currently receiving a new firmware via XMODEM.                                                             |
| _Light Blue_ | Solid | Firmware transfer has been completed | The LED will turn solid light blue once the transfer has been complete. After 10 seconds it will reboot itself and start the final step of the firmware upgrade. |

\
