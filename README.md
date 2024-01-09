- [About](#orgeeaf732)
- [Images](#orga156bbc)
- [Schematic](#org4c67822)
- [PCB](#org63fbb71)
- [Bill of Materials](#orgace9e73)
- [Development](#org7f4c210)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="orgeeaf732"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 4.0
- Kicad Version: 7.0.9
- Release Date: 2024-01-09
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


<a id="orga156bbc"></a>

# Images

<img src="./documentation/pcb/raytrace.png" width="1280px">

<img src="./documentation/pcb/top.png" width="1280px">

<img src="./documentation/pcb/bottom.png" width="1280px">

<img src="./documentation/pcb/front.png" width="1280px">

<img src="./documentation/pcb/back.png" width="1280px">

<img src="./documentation/pcb/left.png" width="1280px">

<img src="./documentation/pcb/right.png" width="1280px">


<a id="org4c67822"></a>

# Schematic

[./documentation/schematic/wingbeat\_detector.pdf](./documentation/schematic/wingbeat_detector.pdf)

<img src="./documentation/schematic/wingbeat_detector.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-power.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-filter.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-photodiode.svg" width="1280px">

<img src="./documentation/schematic/wingbeat_detector-assembly.svg" width="1280px">


<a id="org63fbb71"></a>

# PCB

<img src="./documentation/pcb/wingbeat_detector-User_Drawings.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-F_Silkscreen.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-B_Silkscreen.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-F_Fab.svg" width="1280px">

<img src="./documentation/pcb/wingbeat_detector-B_Fab.svg" width="1280px">


<a id="orgace9e73"></a>

# Bill of Materials


## Board

|    |
|--- |
|  |


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


<a id="org7f4c210"></a>

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
