- [About](#orgfb5bdfd)
- [Images](#orgf778466)
- [Schematic](#org3ba27e5)
- [PCB](#org66b2b22)
- [Bill of Materials](#org462ec89)
- [Development](#orgb49b2b2)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="orgfb5bdfd"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 4.0
- Kicad Version: 7.0.10
- Release Date: 2024-02-06
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


<a id="orgf778466"></a>

# Images

![img](./documentation/pcb/raytrace.png)

![img](./documentation/pcb/top.png)

![img](./documentation/pcb/bottom.png)

![img](./documentation/pcb/front.png)

![img](./documentation/pcb/back.png)

![img](./documentation/pcb/left.png)

![img](./documentation/pcb/right.png)


<a id="org3ba27e5"></a>

# Schematic

[./documentation/schematic/wingbeat\_detector.pdf](./documentation/schematic/wingbeat_detector.pdf)

![img](./documentation/schematic/wingbeat_detector.svg)

![img](./documentation/schematic/wingbeat_detector-power.svg)

![img](./documentation/schematic/wingbeat_detector-filter.svg)

![img](./documentation/schematic/wingbeat_detector-photodiode.svg)

![img](./documentation/schematic/wingbeat_detector-assembly.svg)


<a id="org66b2b22"></a>

# PCB

![img](./documentation/pcb/wingbeat_detector-User_Drawings.svg)

![img](./documentation/pcb/wingbeat_detector-F_Silkscreen.svg)

![img](./documentation/pcb/wingbeat_detector-B_Silkscreen.svg)

![img](./documentation/pcb/wingbeat_detector-F_Fab.svg)

![img](./documentation/pcb/wingbeat_detector-B_Fab.svg)


<a id="org462ec89"></a>

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

<div class="TABLE" id="org2e05214">
<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-right" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-right" />

<col  class="org-right" />

<col  class="org-right" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-right">Item</th>
<th scope="col" class="org-left">Description</th>
<th scope="col" class="org-left">Manufacturer Part Number</th>
<th scope="col" class="org-left">Manufacturer</th>
<th scope="col" class="org-right">Quantity</th>
<th scope="col" class="org-right">Cost</th>
<th scope="col" class="org-right">Total</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-right">1</td>
<td class="org-left">BNC STRAIGHT BULKHEAD JACK TO AM</td>
<td class="org-left">095-850-210-150</td>
<td class="org-left">Amphenol RF</td>
<td class="org-right">1</td>
<td class="org-right">24.41</td>
<td class="org-right">24.41</td>
</tr>


<tr>
<td class="org-right">2</td>
<td class="org-left">AC/DC WALL MNT ADAPTER 5.1V 15W</td>
<td class="org-left">SC0445</td>
<td class="org-left">Raspberry Pi</td>
<td class="org-right">1</td>
<td class="org-right">8.00</td>
<td class="org-right">8.00</td>
</tr>


<tr>
<td class="org-right">3</td>
<td class="org-left">CBL ASSY BNC PLUG-PLUG RG58 5'</td>
<td class="org-left">5697-60</td>
<td class="org-left">Pomona Electronics</td>
<td class="org-right">1</td>
<td class="org-right">21.29</td>
<td class="org-right">21.29</td>
</tr>


<tr>
<td class="org-right">4</td>
<td class="org-left">LLG 3 mm Core 420 - 2000 nm 1.2 m</td>
<td class="org-left">LLG3-4Z</td>
<td class="org-left">thorlabs</td>
<td class="org-right">1</td>
<td class="org-right">392.69</td>
<td class="org-right">392.69</td>
</tr>


<tr>
<td class="org-right">5</td>
<td class="org-left">3 mm LLG to SM1 Adapter</td>
<td class="org-left">AD3LLG</td>
<td class="org-left">thorlabs</td>
<td class="org-right">1</td>
<td class="org-right">38.32</td>
<td class="org-right">38.32</td>
</tr>


<tr>
<td class="org-right">6</td>
<td class="org-left">Adapter External SM05 Internal SM1</td>
<td class="org-left">SM1A1</td>
<td class="org-left">thorlabs</td>
<td class="org-right">1</td>
<td class="org-right">23.41</td>
<td class="org-right">23.41</td>
</tr>


<tr>
<td class="org-right">7</td>
<td class="org-left">SM05 Adjustable Lens Tube</td>
<td class="org-left">SM05V05</td>
<td class="org-left">thorlabs</td>
<td class="org-right">1</td>
<td class="org-right">31.64</td>
<td class="org-right">31.64</td>
</tr>


<tr>
<td class="org-right">8</td>
<td class="org-left">825nm 12.5mm Dia Longpass Filter</td>
<td class="org-left">86-062</td>
<td class="org-left">edmundoptics</td>
<td class="org-right">1</td>
<td class="org-right">194.00</td>
<td class="org-right">194.00</td>
</tr>


<tr>
<td class="org-right">9</td>
<td class="org-left">Universal probe holder</td>
<td class="org-left">MXB</td>
<td class="org-left">siskiyou</td>
<td class="org-right">1</td>
<td class="org-right">275.00</td>
<td class="org-right">275.00</td>
</tr>


<tr>
<td class="org-right">10</td>
<td class="org-left">MACHINE SCREW PAN PHILLIPS 2-56</td>
<td class="org-left">PMSSS 256 0050 PH</td>
<td class="org-left">B&amp;F Fastener Supply</td>
<td class="org-right">4</td>
<td class="org-right">0.24</td>
<td class="org-right">0.96</td>
</tr>


<tr>
<td class="org-right">11</td>
<td class="org-left">HEX NUT 3/16" STN STEEL 2-56</td>
<td class="org-left">HNSS256</td>
<td class="org-left">B&amp;F Fastener Supply</td>
<td class="org-right">4</td>
<td class="org-right">0.28</td>
<td class="org-right">1.12</td>
</tr>
</tbody>

<tbody>
<tr>
<td class="org-right">Total</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
<td class="org-right">&#xa0;</td>
<td class="org-right">&#xa0;</td>
<td class="org-right">1010.84</td>
</tr>
</tbody>
</table>

</div>


<a id="orgb49b2b2"></a>

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
