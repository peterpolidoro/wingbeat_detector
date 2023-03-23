- [About](#orge72f788)
- [Images](#org0d1212f)
- [Schematic](#org7a0836d)
- [PCB](#org4859499)
- [Bill of Materials](#org6ceabb3)
- [Development](#orgb4cc99c)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="orge72f788"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 3.0
- Kicad Version: 7.0.1
- Release Date: 2023-03-23
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


<a id="org0d1212f"></a>

# Images


<a id="org7a0836d"></a>

# Schematic


<a id="org4859499"></a>

# PCB


<a id="org6ceabb3"></a>

# Bill of Materials


<a id="orgb4cc99c"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Clone Repository

```sh
git clone git@github.com:peterpolidoro/wingbeat_detector.git
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