# YetAnotherKeyboard
This is an 80% mechanical keyboard with hot-swappable MX style switches. The design is based on a Raspberry Pi Pico W as the microcontroller.
Alongside the standard 80% layout, there are also 4 programmable macro keys and a 1.54 inch OLED display. It accomodates a standard lithium-polymer
battery cell - I will use a 2000mAh cell I already have on hand. It supports a Micro-USB connection through the Pico's onboard USB port, and wireless
operation due to the Pico's wireless capabities. The onboard battery is charged through a TP4056 by drawing power from the pico while plugged in.

## Repo structure
CAD files including the individual parts and full assembly can be found in `cad/`
The KiCad PCB design files can be found in `PCB/`
Production gerbers can be found in `PCB/production`
Firmware can be found in `firmware/`

## BOM
Total cost: 40.36 USD
All parts are sourced from AliExpress.
Many parts I already own, and therefore there are no links/costs, only qty.

## PCB
Parameters:
* 2 layer
* Material: FR-4
* (Un)leaded HASL
* White solder mask
Dimensions: 414.81mm * 138.11mm
PCB cost: 27 USD
Shipping cost: 18.12 USD
Total cost: 45.12 USD

## Firmware
TBC, most likely ZMK

## Cost
Parts: 40.36 USD
PCB: 45.12 USD
Case: free (3D print)
Grand total: 85.48 USD