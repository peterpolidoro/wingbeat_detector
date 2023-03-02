- [About](#org85e49b6)
- [Images](#org1f435ef)
- [Schematic](#org078cd9f)
- [PCB](#orge5ebc59)
- [Bill of Materials](#org5a9a641)
- [Development](#org1625e12)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org85e49b6"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 3.0.0
- Kicad Version: 7.0.0
- Release Date: 2023-03-01
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


<a id="org1f435ef"></a>

# Images


<a id="org078cd9f"></a>

# Schematic


<a id="orge5ebc59"></a>

# PCB


<a id="org5a9a641"></a>

# Bill of Materials


<a id="org1625e12"></a>

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