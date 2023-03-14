# Kuro65
<img align="right" width="118" height="207" src="https://user-images.githubusercontent.com/28592326/219898869-d1d8c107-8534-48e9-9dfd-22592b35853f.png">
The hot-swappable ISO mechanical keyboard PCB. 

Features include:
- QMK compatible
- Hot-swappable MX sockets
- 65% ISO DE layout
- Multi-layer support


### Table of contents
- [Schematic](#schematic)
- [Bill of Material](#bom)
- [Pictures](#pictures)


# Schematic
<a name="schematic"/>
Standard schematic for a QMK firmware compatible mechanical keyboard.

#### Main schematic:
![schematic_main](https://github.com/0x544D/kuro65/blob/main/pictures/kusabimaru/kuro65_schematic_main.png?raw=true)
#### Switch matrix schematic:
![schematic_switches](https://github.com/0x544D/kuro65/blob/main/pictures/kusabimaru/kuro65_schematic_switches.png?raw=true)

# Bill of Material
<a name="bom"/>

| Qty | Component       | Footprint      | JLC Part Number | Datasheet | Shop URL                                                                 |
|-----|-----------------|----------------|-----------------|-----------|--------------------------------------------------------------------------|
|  1  | ATMEGA32U4-MU   | QFN-44_7x7x05P | C112161         |[Datasheet](https://datasheet.lcsc.com/lcsc/1809032024_Microchip-Tech-ATMEGA32U4-MU_C112161.pdf) | [Link](https://jlcpcb.com/partdetail/MicrochipTech-ATMEGA32U4MU/C112161) |
|  1  | X322516MLB4SI   | SMD3225-4P     | C13738          |[Datasheet](https://datasheet.lcsc.com/lcsc/2103291133_Yangxing-Tech-X322516MLB4SI_C13738.pdf) | [Link](https://jlcpcb.com/partdetail/YangxingTech-X322516MLB4SI/C13738) |
|  1  | B3FS-1000P      | SMD,6x6x3.1mm  | C271750         |[Datasheet](https://omronfs.omron.com/en_US/ecb/products/pdf/en-b3fs.pdf) | [Link](https://jlcpcb.com/partdetail/OmronElectronics-B3FS1000P/C271750) |
|  1  | TYPE-C-31-M-12  | SMD            | C165948         |[Datasheet](https://datasheet.lcsc.com/lcsc/2205251630_Korean-Hroparts-Elec-TYPE-C-31-M-12_C165948.pdf) | [Link](https://jlcpcb.com/partdetail/Korean_HropartsElec-TYPE_C_31_M12/C165948) |
| 70  | CPG151101S11    | SMD            | C2803348        |[Datasheet](https://datasheet.lcsc.com/lcsc/2202281830_Kailh-CPG151101S11_C2803348.pdf) | [Link](https://jlcpcb.com/partdetail/Kailh-CPG151101S11/C2803348) |
| 70  | 1N4148W         | SOD-123        | C109203         |[Datasheet](https://datasheet.lcsc.com/lcsc/1811131721_Shikues-1N4148W_C109203.pdf) | [Link](https://jlcpcb.com/partdetail/Shikues-1N4148W/C109203) |


# Pictures
<a name="pictures"/>

Kuro65 PCB
![kuro65_pcb](https://github.com/0x544D/kuro65/blob/main/pictures/kusabimaru/kuro65_pcb.jpeg?raw=true)
Kuro65 inside TOFU65 case
![kuro65_case](https://github.com/0x544D/kuro65/blob/main/pictures/kusabimaru/kuro65_case.jpeg?raw=true)


# Contributors and Acknowledgements
- Keyswitches based on: [daprice](https://github.com/daprice/keyswitches.pretty)
- Stabilizers used: [perigoso](https://github.com/perigoso/Switch_Keyboard)
