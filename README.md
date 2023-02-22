- [About](#orgd9db781)
- [Images](#org914e6fc)
- [Schematic](#org35b4ae4)
- [PCB](#orgc1c8f48)
- [Bill of Materials](#org4640263)
- [Development](#org9c11d6a)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="orgd9db781"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 3.0.0
- Kicad Version: 7.0.0
- Release Date: 2023-02-22
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


<a id="org914e6fc"></a>

# Images


<a id="org35b4ae4"></a>

# Schematic


<a id="orgc1c8f48"></a>

# PCB


<a id="org4640263"></a>

# Bill of Materials


<a id="org9c11d6a"></a>

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