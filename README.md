- [About](#org9f02d1f)
- [Images](#orgd1339fd)
- [Schematic](#orgeadee9c)
- [PCB](#org2200c52)
- [Bill of Materials](#orgb3a1d96)
- [Development](#orgb1acf10)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org9f02d1f"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 4.0
- Kicad Version: 7.0.9
- Release Date: 2023-12-06
- Creation Date: 2023-02-17
- License: GPL-3.0
- URL: https://github.com/peterpolidoro/wingbeat_detector
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2023 Peter Polidoro
- References:
  - https://www.kicad.org/
  - https://github.com/janelia-kicad/light_sensor_boards
```


<a id="orgd1339fd"></a>

# Images

<img src="./documentation/pcb/raytrace.png" width="1280px">

<img src="./documentation/pcb/top.png" width="1280px">

<img src="./documentation/pcb/bottom.png" width="1280px">

<img src="./documentation/pcb/front.png" width="1280px">

<img src="./documentation/pcb/back.png" width="1280px">

<img src="./documentation/pcb/left.png" width="1280px">

<img src="./documentation/pcb/right.png" width="1280px">


<a id="orgeadee9c"></a>

# Schematic

[./documentation/schematic/wingbeat\_detector.pdf](./documentation/schematic/wingbeat_detector.pdf)

<img src="./documentation/schematic/wingbeat_detector.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-power.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-filter.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-photodiode.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-led.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-assembly.svg" width="1280px">


<a id="org2200c52"></a>

# PCB

<img src="./documentation/pcb/wingbeat_detector-User_Drawings.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-F_Silkscreen.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-B_Silkscreen.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-F_Fab.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-B_Fab.svg" width="1280px">


<a id="orgb3a1d96"></a>

# Bill of Materials


## Board

| Item | Reference(s)                    | Description                      | Manufacturer Part Number | Manufacturer                                | Quantity | Package          |
|---- |------------------------------- |-------------------------------- |------------------------ |------------------------------------------- |-------- |---------------- |
| 1    | C1 C2 C3 C4 C5 C13              | CAP CER 4.7UF 16V X5R 0603       | C1608X5R1C475K080AC      | TDK Corporation                             | 6        |                  |
| 2    | C6 C7 C8 C9 C10 C12             | CAP CER 0.1UF 25V Y5V            | CC0402ZRY5V8BB104        | Yageo                                       | 6        | 0402             |
| 3    | C11                             | CAP CER 2PF 50V C0G              | CGA2B2C0G1H020C050BA     | TDK Corporation                             | 1        | 0402             |
| 4    | D1                              | SENSOR PHOTODIODE RADIAL         | BPD-BQDA38V-FZ04         | American Bright Optoelectronics Corporation | 1        |                  |
| 5    | D2                              | 5MM 940 IR                       | BIR-BM17J8V-FZ04         | American Bright Optoelectronics Corporation | 1        |                  |
| 6    | J1                              | CONN RCP USB3.1 TYPEC 24P SMD RA | 10137062-00021LF         | Amphenol                                    | 1        |                  |
| 7    | J2 J3 J4                        | CONN UMC JACK STR 50 OHM SMD     | A-1JB                    | Amphenol RF                                 | 3        |                  |
| 8    | Q1                              | MOSFET N-CH 30V 1.5A 3PICOSTAR   | CSD17483F4               | Texas Instruments                           | 1        |                  |
| 9    | R1 R3 R6 R8 R10 R11 R12 R14 R16 | RES SMD 49.9K OHM 1% 1/10W       | ERJ-2RKF4992X            | Panasonic Electronic Components             | 9        | 0402             |
| 10   | R2 R4                           | RES SMD 68.1K OHM 1% 1/10W       | ERJ-2RKF6812X            | Panasonic Electronic Components             | 2        | 0402             |
| 11   | R5 R7                           | RES SMD 3.65M OHM 1% 1/10W       | CRCW06033M65FKEA         | Vishay Dale                                 | 2        | 0603             |
| 12   | R9                              | RES SMD 249 OHM 1% 1/10W         | ERJ-2RKF2490X            | Panasonic Electronic Components             | 1        | 0402             |
| 13   | R13 R15                         | RES SMD 23.2K OHM 1% 1/10W       | ERJ-2RKF2322X            | Panasonic Electronic Components             | 2        | 0402             |
| 14   | R17                             | RES SMD 2K OHM 1% 1/10W          | ERJ-2RKF2001X            | Panasonic Electronic Components             | 1        | 0402             |
| 15   | RV1 RV2                         | TRIMMER 500K OHM 0.125W J LEAD   | 3223W-1-504E             | Bourns Inc.                                 | 2        |                  |
| 16   | U1                              | IC REG CHARGE PUMP INV DL 8UMAX  | MAX865EUA+               | Maxim Integrated                            | 1        | SOP65P490X110-8N |
| 17   | U2 U3                           | IC UNIV ACTIVE FILTER 16-SOIC    | UAF42AU                  | Texas Instruments                           | 2        |                  |
| 18   | U4                              | IC TRANSIMPEDANCE 1 CIRCUIT 8SON | OPA381AIDRBT             | Texas Instruments                           | 1        |                  |
| 19   | U5                              | IC OPAMP GP 1 CIRCUIT            | TSV630IQ1T               | STMicroelectronics                          | 1        | 6DFN             |
| 20   | U6                              | IC LED DRIVER LINEAR 50MA        | AB-EZPC-10               | American Bright Optoelectronics Corporation | 1        | 6DFN             |


## Supplemental

| Item | Description                      | Manufacturer Part Number        | Manufacturer       | Quantity |
|---- |-------------------------------- |------------------------------- |------------------ |-------- |
| 1    | BNC STRAIGHT BULKHEAD JACK TO AM | 095-850-210-150                 | Amphenol RF        | 1        |
| 2    | AC/DC WALL MNT ADAPTER 5.1V 15W  | RPI USB-C POWER SUPPLY BLACK US | Raspberry Pi       | 1        |
| 3    | CBL ASSY BNC PLUG-PLUG RG58 6"   | 5697-6                          | Pomona Electronics | 1        |
| 4    | CBL ASSY BNC PLUG-PLUG RG58 5'   | 5697-60                         | Pomona Electronics | 1        |
| 5    | CBL ASSY BNC PLUG-PLUG RG58 10'  | 5697-120                        | Pomona Electronics | 1        |
| 6    | TEST LEAD BNC TO SOCKET 5.6"     | 5069                            | Pomona Electronics | 1        |
| 7    | TEST LEAD BNC TO GRAB HOOK 5.5"  | 5305                            | Pomona Electronics | 1        |


<a id="orgb1acf10"></a>

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
