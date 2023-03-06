- [About](#orgf117e09)
- [Images](#orgc54c97d)
- [Schematic](#org174f0a8)
- [PCB](#orgb4e4cfd)
- [Bill of Materials](#orge362961)
- [Development](#orgd7a2097)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="orgf117e09"></a>

# About

```markdown
- Project Name: wingbeat_detector
- Description: Measures fly wingbeats using IR light reflected from flapping fly wings.
- Version: 3.0.0
- Kicad Version: 7.0.0
- Release Date: 2023-03-06
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


<a id="orgc54c97d"></a>

# Images


<a id="org174f0a8"></a>

# Schematic


<a id="orgb4e4cfd"></a>

# PCB


<a id="orge362961"></a>

# Bill of Materials


<a id="orgd7a2097"></a>

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