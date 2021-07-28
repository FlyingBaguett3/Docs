---
template: main.html
---

![Info Banner](https://github.com/ExpressLRS/ExpressLRS-Hardware/blob/master/img/information.png?raw=true)

# Glossary
Below you can find a list of terms you might not be sure about, as well as some common abbreviations:

- `CRSF`: TBS Crossfire, more specifialy in our case most often refering to the communication protocol between TX and TX module and RX and FC respectively
- `OTX`: OpenTX
- `FW`: Firmware
- `BL`: Bootloader, loads the FW
- `S.Port`: SmartPort, sometimes referred to as `sport`. FrSky "telemetry" protocol. The `S.Port` also gets used for updating FrSky receivers.
- `OTA`: Update your device `Over The Air` (wifi)
- `MCU`: Micro Controller Unit, generally denotes an embedded system controller as opposed to big iron cpu
- `OSD`: On Screen Display, refer to [this page for instructions for setup in BF](https://github.com/AlessandroAU/ExpressLRS/wiki/OpenTX-and-Betaflight-Setup#rssi-and-link-quality)
- `LQ`: Link Quality, percentage of expected packets received. Our preferred method of measuring the quality of the control link
- `RSSI dBm`: Measure of power level measured in dBm. Basically, how strong the signal being received is
- `RSSI`: Received Signal Strength Indicator, "arbitrary" scaled version of `RSSI dBm` or LQ. [Signal Health: LQI and RSSI Explained](https://github.com/ExpressLRS/ExpressLRS/wiki/Signal-Health:-LQI-and-RSSI-Explained)
- `Lua`: Means "Moon" in Portuguese. As such, Lua is the correct way to write and not all uppercase.
The ExpressLRS Lua script can be installed on a OpenTX radio, to easily alter TX parameters like Packet rate, Telemetry ratio and Output power.
But also shows if the radio (OpenTX) is communicating correctly with the module. ( e.g. 0:50, 0:150, 0:200 and so on.)

To be continued.