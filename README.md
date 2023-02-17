- [About](#org3b067b3)
- [Images](#orgb259fcc)
- [Schematic](#orgacdfdcf)
- [PCB](#org40a6a6b)
- [Bill of Materials](#orgeed4f62)
- [Development](#orgc498269)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org3b067b3"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 3.0.0
- Kicad Version: 6.0.11
- Release Date: 2023-02-17
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


<a id="orgb259fcc"></a>

# Images


<a id="orgacdfdcf"></a>

# Schematic


<a id="org40a6a6b"></a>

# PCB


<a id="orgeed4f62"></a>

# Bill of Materials


<a id="orgc498269"></a>

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