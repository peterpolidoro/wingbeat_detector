- [About](#orgc184f91)
- [Images](#orgda54458)
- [Schematic](#orgf420d70)
- [PCB](#orgb6b697f)
- [Bill of Materials](#org148434a)
- [Development](#org2408e28)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="orgc184f91"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 3.0.0
- Kicad Version: 6.0.11
- Release Date: 2023-02-21
- Creation Date: 2023-02-17
- License: BSD-3-Clause
- URL: https://github.com/janelia-kicad/wingbeat_detector
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2023 Howard Hughes Medical Institute
- References:
  - https://www.kicad.org/
  - https://github.com/janelia-kicad/light_sensor_boards
```


<a id="orgda54458"></a>

# Images


<a id="orgf420d70"></a>

# Schematic


<a id="orgb6b697f"></a>

# PCB


<a id="org148434a"></a>

# Bill of Materials


<a id="org2408e28"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Clone Repository

```sh
git clone git@github.com:janelia-kicad/wingbeat_detector.git
cd wingbeat_detector
```


## Edit metadata.org

```sh
make -f .metadata/Makefile metadata-edits
```


## Tangle metadata.org

```sh
make -f .metadata/Makefile metadata
```


## Edit project

```sh
make -f .metadata/Makefile project-edits
exit
```