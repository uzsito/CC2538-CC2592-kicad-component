# CC2538-CC2592-kicad-component
This repository contains schematic symbol, pcb footprint, and 3D model for a particular chinese CC2538-CC2592 Zigbee RF module. All files are provided to import the module to Kicad as a new component. 

## Module specification
![module](graphics/module.jpg)
This zigbee RF unit is pretty common, very cheap and easy-to-get from China. A couple of custom zigbee coordinator designs have been made using this part as a base. The applied CC2538 is a stable, powerful zigbee SoC with USB capability, backed up by CC2592 RF frontend. In my opinion, this is the best integrated zigbee RF solution you can get at the moment.

| Property | Value |
| -------- | ----- |
| Frequency band | 2.4GHz |
| Input gain | 12dB |
| Receiving current | 30mA |
| Transmission current | <175mA |
| Output power | +20dBm |
| Operating voltage | 3.3V |
| Data rate | 250Kbps |
| Number of channels | 16 |
| Antenna | PCB or IPEX |
| Module size | 20.5mm×33mm |
| Pitch | 1.27mm |

## Kicad instances

![render1](graphics/render1.jpg)
![render2](graphics/render2.jpg)
![render3](graphics/render3.jpg)

## Installation
To be able to work with the module in Kicad, clone the repository, and copy the files to directories mentioned below.
| Filename  | Directory |
| --------- | --------- |
| Schematic | Kicad/ |
| Footprint | Kicad/ |
| 3D Model | Kicad/ |
