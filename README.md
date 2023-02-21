- [About](#orgc1fecc9)
- [Images](#org39c71fa)
- [Schematic](#org370b9e8)
- [PCB](#org07ce663)
- [Bill of Materials](#org8d6384d)
- [Development](#orgdced7a9)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="orgc1fecc9"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 3.0.0
- Kicad Version: 7.0.0
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


<a id="org39c71fa"></a>

# Images


<a id="org370b9e8"></a>

# Schematic


<a id="org07ce663"></a>

# PCB


<a id="org8d6384d"></a>

# Bill of Materials


<a id="orgdced7a9"></a>

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