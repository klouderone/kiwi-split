# The Kiwi 36 Split
The kiwi 36 split is the perfect split keyboard for absolute beginners, while also being packed full of features such as USB-C interconnect, battery support and 3 kinds of switches.
The kiwi 36 is easy to build, having the option to use mostly through-hole components, and bigger pads for surface mount components. 

The kiwi is a minimalist board, aimed to be as compact as possible, yet very easy to build, with the ability to use either leaded diodes or surface mount diodes.
It is inteneded to be used with home row-mods.

Please make sure to read everything before building or using.

## Features
- **USB-C** interconnect for wired builds
- Hotswap **MX**, Hotswap **Choc V1** and Hotswap **Gateron Low Profile** switch support
- **MX Spaced** (19.05mm x 19.05mm)
- Both **Leaded and Surface Mount Diode Support** for both beginner and advanced builders
- **Larger pads** for surface mount components
- Inbuilt battery switch 
- Inbuilt Nice!View display support
- Both PH2 connector and solder pads for batteries, with an included hole for bigger batteries under the PCB
- Waffle Pattern PCB

## Bill Of Materials

These can all be sourced from www.keaworkshop.com, or can be sourced yourself. 

### Required

| Name                          | Count   | Remarks                                                                                     |
|:------------------------------|:--------|:--------------------------------------------------------------------------------------------|
| PCB                           | 1 set   |                                                                                             |
| Case                          | 1 set   | 3D printable                                                                                            |
| Switch plate                  | 1 set   | FR4 1.6mm thick                                                                             |
| Microcontroller               | 2       | ATmega32u4 (wired), RP2040 (wired), Nice!Nano V2 (wireless), Supermini NRF52840 (wireless)  |
| Key switches                  | 36      | Cherry MX or Choc V1 or Gateron Low Profile                                                 |
| Keycaps                       | 36      | 1u 40 pcs, 1.5u 2 pcs                                                                       |
| Hotswap Sockets               | 36      | 36x Cherry MX or Gateron Low Profile and 36x Choc V1.                                     |
| USB C Daughter Board          | 2       | https://www.aliexpress.com/item/1005005187678366.html                                       |
| Type-C cable                  | 1       |                                                                                             |
| Diodes                        | 36      | SOD-123 or 1N4148 Leaded Diodes                                                             |
| Keycaps                       | 36      | 1u 34 pcs, 1.5u 2 pcs                                                                       |
| Mill-Max Pins                 | 48      |                                                                                             |
| Mill-Max Socket (12 Pin)      | 4       |                                                                                             |
| Tactile Button (6mm x 3mm x 4.3mm) | 2       |                                                                                             |
| PH2 Battery Connector (Right Angle) | 2       |  only needed for wireless builds www.aliexpress.com/item/1005006027334406.html                                               |
| MSK-12C02 / PCM12SMTR Toggle Switch | 2       |  only needed for wireless builds                                         |

### Optional

| Name                          | Count   | Remarks                                                                                     |
|:------------------------------|:--------|:--------------------------------------------------------------------------------------------|
| Display                       | 2       | Nice!View (ZMK only) or .91 OLED Display                                                               |
| 4 Pin Header                 | 2       |  for .91 OLED Display                                                                                       |
| 5 Pin Header   | 2 | for Nice!View (usually included with Nice!View)
| Battery                 | 2       | Leaded or PH2 connector                                                |

## IMPORTANT

**ALWAYS make sure that you DO NOT plug the USB-C interconnect cable into the host device (Computer, Laptop, iPad)**. This **WILL** result in the microcontroller being broken, and needing to be replaced.
I plan to design some protection against this, though i need to figure out how to do this with parts that are not surface mounted, and can be soldered by the consumer.

## Build Guide

## Firmware

## Pictures

PCBs
![image](https://github.com/user-attachments/assets/42b4ee55-afd8-48ba-817e-26e9f39e5572)
Schematic
![image](https://github.com/user-attachments/assets/f8483d3e-f5d2-4615-abce-0e77aa9b9c7d)

