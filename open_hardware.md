
## WIP Solar repeater

Warning: Currently untested. Fabricate at own risk

* [WIP Carrier board](https://easyeda.com/editor#id=592064109fa14cb9928a27941568b825) 2x Xiao connected with UART, Extended SPI flash, Solar/ battery control, Mikro click header ~$10pc
* [WIP 2.4Ghz Lora Click board](https://easyeda.com/editor#id=6d2e6629ff40472cb557240839030eae) SX1280 in Mikro format ~$10pc
* [WIP Optional supplimental/ standalone battery board](https://easyeda.com/editor#id=32531419fb5846f99fff6a716b25fd8e) Provides 3.3v with over/under voltage & temp protection ~$5pc
* [XIAO NRF52](https://wiki.seeedstudio.com/XIAO_BLE/#seeed-studio-xiao-nrf52840) Nrf52/ ESP32 etc ~$15 (other Xiao boards also possible)

The above is intended for experiments with dual radio 2.4Ghz/ 868Mhz LoRa, can also be used as a standard ~868Mhz/ 915Mhz repeater.

Todo: Updated schematics
  
## Ancillary components 
* [Enclosure](https://www.aliexpress.com/item/1005006751970338.html) ~$22
* [5V panel](https://www.aliexpress.com/w/wholesale-20watt-5v-solar-.html) ~$10
* [21700 battery](https://www.aliexpress.com/w/wholesale-21700-battery.html) ~$6

## What is it for?
* Primary use case is to explore [bridging Meshcore (868Mhz) over Retuculum (2.4Ghz)](https://github.com/samuk/Reticulum/blob/master/docs/meshcore-bridge.md)
* It could also be used with two 868Mhz radios on different channels if sufficient antenna spacing was achieved, eg the [Mikro click boards](https://www.mikroe.com/click/wireless-connectivity/lora)
* It could just be a single radio 868Mhz repeater with an empty slot
  

## Alternate power solutions  
* [ALT Proprietary battery (Expensive)](https://www.aliexpress.com/item/1005009840834258.html)
* [Charge control (W temp, no 3.3v)](https://easyeda.com/editor#id=4d89498e7f9949fda46f6c9299993ad9)
* [Aliexpress Charge control (no temp control)](https://www.aliexpress.com/w/wholesale-SD05CRMA-pins.html) (no 3v regulation of low voltage protection)

## Alternate PCB's

| Project | Link | MCU | LoRa | Standout Features |
|---|---|---|---|---|
| **meshtastic设备-Fucktec** | [oshwhub.com](https://pro.easyeda.com/editor#id=856ffe4c3d064868a1c88e3aa3d39bd1) | nRF52 | LoRa module | FakeTec variant with screen, GPS, and an onboard MPPT solar charge controller squeezed into the original FakeTec footprint; circuits are modular so sections can be omitted [Pro Micro](https://github.com/sasodoma/nrf52840-promicro)|
| **meshtastic nrf52840 mgt** | [oshwhub.com](https://oshwhub.com/mgt19937/meshtastic-nrf52840-prototype_2024-10-22_00-31-47) | nRF52840 (Pro Micro) | LoRa module | Fully handmade handheld node; reworked antenna layout specifically for the Pro Micro footprint; ¥100 to clone |
| **meshtastic-mini** | [oshwhub.com](https://oshwhub.com/SHENYE894) | nRF52840 | LoRa module | Single-node device with optimised nRF52840 Bluetooth antenna section for extended BT range |
| **meshtastic太阳能端** | [oshwhub.com](https://oshwhub.com/allrounderkali) | nRF52 | LoRa module | Dedicated solar repeater/endpoint; solar panel power is selectable based on target power budget |
| **TinyLoRa-C3 MV 手持** | [oshwhub.com](https://oshwhub.com/kangyuzhe) | ESP32-C3 | LLCC68 / SX1262 (22–29 dBm) | Most feature-packed handheld on the list: barometric pressure, temp/humidity, 5-way joystick, GPS, LiPo, buzzer, WiFi, BT — one board; also supports MeshCore |
| **基于ESP32C6的全功能meshtastic节点** | [oshwhub.com](https://oshwhub.com/kazagumo) | ESP32-C6 | Ebyte E22-400M30S | Display + buzzer + RGB LED + joystick, all hardware-verified; one of the only ESP32-C6 Meshtastic designs on the platform |
| **TinyLora-C3 V4.1** | [oshwhub.com](https://oshwhub.com/kangyuzhe) | ESP32-C3 | 22/29/30/33 dBm modules | Wide-input power (USB-C, 7–36 V, or LiPo), built-in solar charge circuit, supports high-power modules up to 33 dBm; Meshtastic & MeshCore compatible |
| **lorawan迷你终端-随身meshtastic-温湿度计** | [oshwhub.com](https://oshwhub.com/kangyuzhe) | ESP32-C3 | SX1262 | Pocket-sized verified build with onboard AHT30 temperature/humidity sensor for environmental mesh telemetry |
| **SakuraPi Pocket Namiji** | [oshwhub.com](https://oshwhub.com/sakurapi/sakurapi-pocket-namiji) | — | LoRa module | Ultra-compact community platform for Meshtastic/LoRaMesh with full 3D-printable case files and firmware docs; flexible power; designed for solar nodes and indoor fixed deployments |
| **TinyLoRa-C3开发板** | [oshwhub.com](https://oshwhub.com/kangyuzhe/esp32c3-ra-01sc-kai-fa-ban-v0-1) | ESP32-C3FH4 (~¥7) | LLCC68 / multi-module | Base dev board for the kangyuzhe lineup; 1 mm PCB for improved antenna performance; 5 LoRa modules tested and verified |
