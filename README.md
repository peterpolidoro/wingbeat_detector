- [About](#org3eb689e)
- [Images](#org308d0a5)
- [Schematic](#org621daf6)
- [PCB](#org7617a64)
- [Bill of Materials](#org0575bf0)
- [Development](#orgc842210)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org3eb689e"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 3.0.0
- Kicad Version: 7.0.0
- Release Date: 2023-03-21
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


<a id="org308d0a5"></a>

# Images


<a id="org621daf6"></a>

# Schematic


<a id="org7617a64"></a>

# PCB


<a id="org0575bf0"></a>

# Bill of Materials


<a id="orgc842210"></a>

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