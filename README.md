# Kuro65
The hot-swappable ISO mechanical keyboard PCB. 

Features include:
- QMK compatible
- Hot-swappable MX sockets
- Multi-layer support

### Table of contents
- [Schematic](#schematic)
- [Bill of Material](#bom)
- [Pictures](#pictures)
- [Plate](#plate)


# Schematic
<a name="schematic"/>
Standard schematic for a QMK firmware compatible mechanical keyboard.

#### Main schematic:
![schematic_main](https://github.com/0x544D/kuro65/blob/main/pictures/kusabimaru/kuro65_schematic_main.png?raw=true)
#### Switch matrix schematic:
![schematic_switches](https://github.com/0x544D/kuro65/blob/main/pictures/kusabimaru/kuro65_schematic_switches.png?raw=true)

# Bill of Material
<a name="bom"/>

| Qty | Component       | Footprint     | Datasheet | Shop URL                                                                                                                    |
| --- | --------------- | ------------- | --------- | --------------------------------------------------------------------------------------------------------------------------- |
| 2   | 1uF             | 0805          |           | [Link](https://de.farnell.com/avx/08053c105kat2a/kondensator-1-f-25v-10-x7r-0805/dp/1658877?st=0805%201%20uf)               |
| 6   | 100nF           | 0805          |           | [Link](https://de.farnell.com/avx/08051c104k4t2a/kondensator-0-1-f-100v-10-x7r/dp/1833888?st=0805%201%20uf)                 |
| 2   | 22pF            | 0805          |           | [Link](https://de.farnell.com/samsung-electro-mechanics/cl21c220jb61pnc/cap-aec-q200-22pf-50v-mlcc-0805/dp/3516161)         |
| 1   | 4,7uF           | 0805          |           | [Link](https://de.farnell.com/samsung-electro-mechanics/cl21a475kaqnnne/kondensator-4-7uf-25v-mlcc-0805/dp/3013462)         |
| 71  | 1N4148          | SOD-323       |           | [Link](https://de.farnell.com/diodes-inc/1n4148ws-7-f/schaltdiode-ss-75v-0-2w-sod323/dp/1843678?st=1n4148%20diode)          |
| 2   | 22R             | 0805          |           | [Link](https://de.farnell.com/multicomp/mcwr08x22r0ftl/dickschichtwiderstand-22r-1-0/dp/2447609?st=0805%20widerstand)       |
| 2   | 5k1             | 0805          |           | [Link](https://de.farnell.com/multicomp/mcwr08x5101ftl/dickschichtwiderstand-5k1-1-0/dp/2447692?st=0805%20widerstand)       |
| 2   | 10k             | 0805          |           | [Link](https://de.farnell.com/vishay/crcw080510k0fkeahp/dickschichtwiderstand-10k-1-0/dp/1738972?st=0805%20widerstand)      |
| ~75 | Kailh SW socket |               | [Datasheet](https://www.kailhswitch.com/uploads/201815927/PG151101S11.pdf)                                       | [Link](https://kbdfans.com/products/mechanical-keyboard-switches-kailh-pcb-socket)                                          |
| 1   | Omron B3FS-1000 | Omron B3FS    | [Datasheet](https://omronfs.omron.com/en_US/ecb/products/pdf/en-b3fs.pdf)                                        | [Link](https://de.farnell.com/omron/b3fs-1000/taster-0-05a-24v-dc-beleuchtet/dp/3121161?st=omron%20b3fs-1000)               |
| 1   | Atmega32U4-AUR  | TQFP-44       | [Datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-7766-8-bit-AVR-ATmega16U4-32U4_Datasheet.pdf) | [Link](https://de.farnell.com/microchip/atmega32u4-aur/mcu-8bit-atmega-16mhz-tqfp-44/dp/2443182?st=atmega32u4)              |
| 1   | USB4085-GF-A    | USB-C         | [Datasheet](https://gct.co/de/connector/usb4085)                                                                 | [Link](https://de.farnell.com/gct-global-connector-technology/usb4085-gf-a/usb-buchse-2-0-typ-c-16pos/dp/2924867?st=usb%20c)|
| 1   | TSX3225 - 16MHz | SMD 3,2x2,5mm | [Datasheet](https://support.epson.biz/td/api/doc_check.php?dl=brief_TSX-3225&lang=en)                            | [Link](https://de.farnell.com/epson/x1e0000210013-tsx-3225-16-mhz-9-0pf/quarz-tsx-3225-16mhz-9pf/dp/1712841?st=tsx3225)     |

# BOM (JLCPCB)

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

Front side of PCB
![3d_front](https://github.com/0x544D/kuro65/blob/main/pictures/kusabimaru/kuro65_front.jpg?raw=true)
Back side with components of the PCB
![3d_back](https://github.com/0x544D/kuro65/blob/main/pictures/kusabimaru/kuro65_back.jpg?raw=true)
![3d_diag](https://github.com/0x544D/kuro65/blob/main/pictures/kusabimaru/kuro65_diag.jpg?raw=true)

# Plate
<a name="plate"/>

TODO:
- generate plate via [swillkb](http://builder.swillkb.com/) by using the [Keyboard Layout Editor](http://www.keyboard-layout-editor.com/) output.
- adapt plate for KBDfans case

# Contributors and Acknowledgements
- Keyswitches based on: [daprice](https://github.com/daprice/keyswitches.pretty)
- Stabilizers used: [perigoso](https://github.com/perigoso/Switch_Keyboard)
