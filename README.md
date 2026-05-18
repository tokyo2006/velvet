## Velvet v3 is a curved, compact mechanical keyboard with a 40% layout size  
*Minimalist, compact, elegant - there is nothing superfluous in it, only the necessary set of elements to know yourself and the harmony of your own world... A wireless version is also available: [Velvet v3 – Wireless Edition](https://eh.works/shop/tproduct/767494027-641661295972-velvet-v3-wireless-edition)*

![Velvet v3](images/01.jpg)

## Design philosophy
This keyboard [was made](https://www.youtube.com/watch?v=800tXbrIh_E) with FDM printing in mind, the goal was to make a perfect curved case that can be easily printed and looks aesthetically pleasing with minimal amount of so called "steps" that plague similar 3D keyboards like Dactyl Manuform. This is mostly inspired by the Cygnus, Smudge and Chonky Bois keyboards, we wanted to make a similar "organic" shaped keyboard but much more optimized for FDM printing, easy assembly and looking good not only on a photo but also in real life 😎

![Velvet v3](images/02.jpg)
![Velvet v3](images/03.jpg)


## Features

- Ergonomic 3D design
- 46 fully programmable keys, 15 additional layers for all your tasks
- Hot-swappable PCB

### Velvet v3
- Powered by RP2040 and QMK firmware
- USB-C connection between halves
- Easily remap any key and customize your keyboard with [Vial](https://eh.industries/vial)

### Velvet v3 – Wireless Edition
- Powered by nRF52840 and RMK/ZMK firmware
- Bluetooth connectivity for up to 6 devices
- 120 mAh battery with up to 3 weeks of use
- USB-C connection

![Velvet v3](images/04.png)

## This repo contains all files related to this keyboard
PCB and schematic can be found [here](https://oshwlab.com/yuriiq/velvet_v3)

### Build guide (handwired)
- [English](https://github.com/ergohaven/velvet/blob/main/handwired/handwired.en.md)
- [Russian](https://github.com/ergohaven/velvet/blob/main/handwired/handwired.md)

### Build guide (PCB is required)
- [English](https://github.com/ergohaven/velvet/blob/main/build_guide/build_guide_en.md)
- [Russian](https://github.com/ergohaven/velvet/blob/main/build_guide/build_guide_ru.md)

### BOM

#### Velvet v3

| Components | Quantity (pcs) |
| --- | ---: |
| RP2040 Zero MCU | 2 |
| MX Hotswap sockets | 46 |
| 1N4148W Diodes (SOD-123) | 46 |
| Male Pin Header Connector: 11 Pins, 2.54mm, 90 degree | 2 |
| Female Header Sockets: 11 Pins, 2.54mm, 90 degree | 2 |
| 10kOhm resistors (0805) | 4 |
| USB Type-C daughterboard: 1.6mm thick | 1 |
| M2x4 Screws | 30 |
| M3x4 Inserts | 10 |
| M3x4 Screws | 10 |
| Type-C to Type-C data cable | 1 |

#### Velvet v3 – Wireless Edition

| Components | Quantity (pcs) |
| --- | ---: |
| nRF52840 controller modules | 2 |
| MX Hotswap sockets | 46 |
| 1N4148W Diodes (SOD-123) | 46 |
| Male Pin Header Connector: 11 Pins, 2.54mm, 90 degree | 2 |
| Female Header Sockets: 11 Pins, 2.54mm, 90 degree | 2 |
| 10kOhm resistors (0805) | 4 |
| Rechargeable Li-Po battery, 200 mAh | 2 |
| USB Type-C daughterboard: 1.6mm thick | 1 |
| M2x4 Screws | 30 |
| M3x4 Inserts | 10 |
| M3x4 Screws | 10 |
| Type-C to Type-C data cable | 1 |

## License 

The files in this repository are licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License

## Firmware
- [Pre-compiled files](https://github.com/ergohaven/keymap_hub)
- [Source code](https://github.com/ergohaven/vial-qmk)

## Availability
The complete keyboard (not a diy kit!) is available for purchase at [eh.industries](https://eh.industries/)
