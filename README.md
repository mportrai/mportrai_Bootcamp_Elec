# mportrai_Bootcamp_Elec

## Liste des composants utilises:
| **Reference**  | **Qty** | **Value** | **DNP** | **Excl. BOM** | **Excl. Board** | **Footprint** | **Datasheet** |
|----------------|-----|------------------------|-----|-----------|-------------|------------------------------------------------|---------------|
| C1, C2         | 2   | Condensateur 12 pF     |     |           |             | mportrai_footprints:CL10C120JB8NNNC            | [Datasheet](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/658/CL10A105KB8NNNC_Spec.pdf) |
| C3, C4, C7     | 3   | Condensateur 100 nF    |     |           |             | mportrai_footprints:CC0603KRX7R9BB104          | [Datasheet](https://www.yageogroup.com/content/datasheet/asset/file/UPY-GPHC_X7R_6_3V-TO-250V) |
| C6             | 1   | Condensateur 1 uF      |     |           |             | mportrai_footprints:CL10A105KB8NNNC            | [Datasheet](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/658/CL10A105KB8NNNC_Spec.pdf) |
| D1             | 1   | LED Green              |     |           |             | mportrai_footprints:TZ-P2-0603YGTCS1-0.6T      | [Datasheet](https://xonstorage.z8.web.core.windows.net/pdf/tuozhan_tzp20603ygtcs106t_apr22_xonlink.pdf) |
| D2             | 1   | LED Red                |     |           |             | mportrai_footprints:XL-1608SURC-06             | [Datasheet](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/6472/5962_XL-1608SURC-06%20%20%200603%E7%BA%A20.6T.pdf) |
| J1, J2         | 2   | ~                      |     |           |             | mportrai_footprints:Connecteur_1               | [Datasheet]() |
| J3             | 1   | FTDI                   |     |           |             | mportrai_footprints:Connecteur_2               | [Datasheet]() |
| R1             | 1   | Résistance 330 Ω       |     |           |             | mportrai_footprints:0603WAF3300T5E             | [Datasheet](https://www.lcsc.com/datasheet/C23138.pdf) |
| R2, R3         | 2   | Résistance 10 kΩ       |     |           |             | mportrai_footprints:RC0603FR-0710KL            | [Datasheet](https://www.yageogroup.com/content/datasheet/asset/file/PYU-RC_GROUP_51_ROHS_L) |
| SW1            | 1   | SW_Push                |     |           |             | mportrai_footprints:B3U-1000P                  | [Datasheet](https://omronfs.omron.com/en_US/ecb/products/pdf/en-b3u.pdf) |
| U1             | 1   | ATmega328P-A           |     |           |             | mportrai_footprints:ATMEGA328P-AU              | [Datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/ATmega48A-PA-88A-PA-168A-PA-328-P-DS-DS40002061B.pdf) |
| Y1             | 1   | Cristal 16 MHz         |     |           |             | mportrai_footprints:X322516MLB4SI              | [Datasheet](https://jlcpcb.com/api/file/downloadByFileSystemAccessId/8588879072148017152) |


## Pin Layout
| **PIN number** | **Label Connecteur J1** | **Label Connecteur J2** | **Label Connecteur J3** |
|----------------|-------------------------|-------------------------|-------------------------|
| 1 | D9 | RAW | DTR |
| 2 | D8 | GND | TX0 |
| 3 | D7 | RST | RXI |
| 4 | D6 | VCC | VCC |
| 5 | D5 | A3 | GND |
| 6 | D4 | A2 | GND |
| 7 | D3 | A1 | x |
| 8 | D2 | A0 | x |
| 9 | GND | SCK | x |
| 10 | RST | MISO | x |
| 11 | RXI | MOSI | x |
| 12 | TX0 | D10 | x |
