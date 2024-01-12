- [About](#org9b99c5a)
- [Images](#orgfaf241b)
- [Schematic](#orgfb528ca)
- [PCB](#org0754e76)
- [Bill of Materials](#orgdc93c9e)
- [Development](#org9b25b3e)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org9b99c5a"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 4.0
- Kicad Version: 7.0.9
- Release Date: 2024-01-12
- Creation Date: 2023-02-17
- License: GPL-3.0
- URL: https://github.com/peterpolidoro/wingbeat_detector
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2024 Peter Polidoro
- References:
  - https://www.kicad.org/
  - https://github.com/janelia-kicad/light_sensor_boards
```


<a id="orgfaf241b"></a>

# Images

<img src="./documentation/pcb/raytrace.png" width="1280px">

<img src="./documentation/pcb/top.png" width="1280px">

<img src="./documentation/pcb/bottom.png" width="1280px">

<img src="./documentation/pcb/front.png" width="1280px">

<img src="./documentation/pcb/back.png" width="1280px">

<img src="./documentation/pcb/left.png" width="1280px">

<img src="./documentation/pcb/right.png" width="1280px">


<a id="orgfb528ca"></a>

# Schematic

[./documentation/schematic/wingbeat\_detector.pdf](./documentation/schematic/wingbeat_detector.pdf)

<img src="./documentation/schematic/wingbeat_detector.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-power.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-filter.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-photodiode.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-assembly.svg" width="1280px">


<a id="org0754e76"></a>

# PCB

<img src="./documentation/pcb/wingbeat_detector-User_Drawings.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-F_Silkscreen.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-B_Silkscreen.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-F_Fab.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-B_Fab.svg" width="1280px">


<a id="orgdc93c9e"></a>

# Bill of Materials


## Board

| Item | Reference(s)   | Description                      | Manufacturer Part Number | Manufacturer                                | Quantity | Package          |
|---- |-------------- |-------------------------------- |------------------------ |------------------------------------------- |-------- |---------------- |
| 1    | C1 C2 C3 C4 C5 | CAP CER 4.7UF 16V X5R 0603       | C1608X5R1C475K080AC      | TDK Corporation                             | 5        |                  |
| 2    | C6 C7 C8 C9    | CAP CER 0.1UF 25V Y5V            | CC0402ZRY5V8BB104        | Yageo                                       | 4        | 0402             |
| 3    | C10            | CAP CER 1UF 35V X5R              | CL05A105KL5NRNC          | Samsung Electro-Mechanics                   | 1        | 0402             |
| 4    | C11            | CAP CER 30PF 50V C0G/NP0         | C0402C300J5GACAUTO       | KEMET                                       | 1        | 0402             |
| 5    | D1             | SENSOR PHOTODIODE RADIAL         | BPD-BQDA38V-FZ04         | American Bright Optoelectronics Corporation | 1        |                  |
| 6    | J1             | CONN RCP USB3.1 TYPEC 24P SMD RA | 10137062-00021LF         | Amphenol                                    | 1        |                  |
| 7    | J2 J3          | CONN UMC JACK STR 50 OHM SMD     | A-1JB                    | Amphenol RF                                 | 2        |                  |
| 8    | R1 R3 R6 R8    | RES SMD 49.9K OHM 1% 1/10W       | ERJ-2RKF4992X            | Panasonic Electronic Components             | 4        | 0402             |
| 9    | R2 R4          | RES SMD 68.1K OHM 1% 1/10W       | ERJ-2RKF6812X            | Panasonic Electronic Components             | 2        | 0402             |
| 10   | R5 R7          | RES SMD 3.65M OHM 1% 1/10W       | CRCW06033M65FKEA         | Vishay Dale                                 | 2        | 0603             |
| 11   | R9             | RES SMD 249 OHM 1% 1/10W         | ERJ-2RKF2490X            | Panasonic Electronic Components             | 1        | 0402             |
| 12   | R10            | RES SMD 150K OHM 0.1% 1/4W       | ERA-8AEB154V             | Panasonic Electronic Components             | 1        | 1206             |
| 13   | R11            | RES 2.0M OHM 1% 0.66W            | ERJ-PM8F2004V            | Panasonic Electronic Components             | 1        | 1206             |
| 14   | U1             | IC REG CHARGE PUMP INV DL 8UMAX  | MAX865EUA+               | Maxim Integrated                            | 1        | SOP65P490X110-8N |
| 15   | U2 U3          | IC UNIV ACTIVE FILTER 16-SOIC    | UAF42AU                  | Texas Instruments                           | 2        |                  |
| 16   | U4             | IC TRANSIMPEDANCE 1 CIRCUIT 8SON | OPA381AIDRBT             | Texas Instruments                           | 1        |                  |


## Supplemental

| Item | Description                        | Manufacturer Part Number | Manufacturer        | Quantity | Cost   |
|---- |---------------------------------- |------------------------ |------------------- |-------- |------ |
| 1    | BNC STRAIGHT BULKHEAD JACK TO AM   | 095-850-210-150          | Amphenol RF         | 1        | 24.41  |
| 2    | AC/DC WALL MNT ADAPTER 5.1V 15W    | SC0445                   | Raspberry Pi        | 1        | 8.00   |
| 3    | CBL ASSY BNC PLUG-PLUG RG58 5'     | 5697-60                  | Pomona Electronics  | 1        | 21.29  |
| 4    | LLG 3 mm Core 420 - 2000 nm 1.2 m  | LLG3-4Z                  | thorlabs            | 1        | 392.69 |
| 5    | 3 mm LLG to SM1 Adapter            | AD3LLG                   | thorlabs            | 1        | 38.32  |
| 6    | Adapter External SM05 Internal SM1 | SM1A1                    | thorlabs            | 1        | 23.41  |
| 7    | SM05 Adjustable Lens Tube          | SM05V05                  | thorlabs            | 1        | 31.64  |
| 8    | 825nm 12.5mm Dia Longpass Filter   | 86-062                   | edmundoptics        | 1        | 194.00 |
| 9    | Universal probe holder             | MXB                      | siskiyou            | 1        | 275.00 |
| 10   | MACHINE SCREW PAN PHILLIPS 2-56    | PMSSS 256 0050 PH        | B&F Fastener Supply | 4        | 0.24   |
| 11   | HEX NUT 3/16" STN STEEL 2-56       | HNSS256                  | B&F Fastener Supply | 4        | 0.28   |
|      |                                    |                          |                     |          |        |


<a id="org9b25b3e"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Edit metadata.org

    make -f .metadata/Makefile metadata-edits


## Tangle metadata.org

    make -f .metadata/Makefile metadata


## Edit project

    make -f .metadata/Makefile kicad-edits
    exit
