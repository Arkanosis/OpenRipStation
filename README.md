# OpenRipStation (ORS) [![License](https://img.shields.io/badge/license-ISC-blue.svg)](/LICENSE)

**OpenRipStation** (ORS for short) is an open-design audio CD ripping station built with on-the-shelf components and free software.

TODO: photo of the result

## Features

### Core features

OpenRipStation allows its users to rip audio CDs to properly tagged lossless FLAC files with minimal interaction and very high reliability.

It's cheap, small, easy to build, easy to customize and easy to repair.

### Variants

OpenRipStation can either:
 - be plugged to a Linux PC using USB to use its computing power for FLAC encoding and its internal storage for the FLAC files, or
 - include a cheap single-board computer (eg. a Raspberry Pi) to make it standalone and portable.

## Usage

### PC variant

 - Plug the OpenRipStation to a PC and to the power supply.
 - Start the OpenRipStation driver on the PC.
 - Every time a tray opens and a sound is played, replace the CD and close the tray.

### Standalone variant

 - Plug a flash drive or an external hard drive to the OpenRipStation.
 - Plug the OpenRipStation to the power supply.
 - Every time a tray opens and a sound is played, replace the CD and close the tray.

## Building

### Required skills

No advanced hardware skill is needed to build an OpenRipStation: there's no soldering, no 3D-printing… only a few USB cables to plug.

Some basic Linux skills can help to setup the software part properly.

No hardware or software skill is needed to *use* the OpenRipStation.

### Bill of materials

To build a N-trays OpenRipStation, you need:

 - N external USB CD drives
 - 1 powered USB hub with N ports (USB 2.0 provides enough bandwidth for up to 64 48X drives)
 - Strong, double-sided tape

![Photo of required parts](/images/01.jpg?raw=true)

| Part      | Quantity | Unit price | Total price |
| :-------- | -------: | ---------: | ----------: |
| CD drives |        3 |       26 € |        78 € |
| USB hub   |        1 |       28 € |        28 € |
| Tape      |        1 |        9 € |         9 € |
|           |          |            |             |
| Total     |          |            |       115 € |

Optionaly, you may want to have:

 - 1 USB extension cable to plug the OpenRipStation to a PC
 - N short USB cables if the ones that come with the CD drives are too long

![Photo of optional parts](/images/02.jpg?raw=true)

| Part       | Quantity | Unit price | Total price |
| :--------- | -------: | ---------: | ----------: |
| USB cable  |        1 |        8 € |         8 € |
| USB cables |        3 |        5 € |        15 € |
|            |          |            |             |
| Total      |          |            |        23 € |

For the standalone variant, you also need:

 - 1 Raspberry Pi (TODO: benchmark models, recommend the cheapest which is fast enough)
 - 1 SD card (16 GiB is more than enough; TODO: document the absolute minimum needed)

TODO: photo

| Part          | Quantity | Unit price | Total price |
| :------------ | -------: | ---------: | ----------: |
| Raspberry Pi  |        1 |       35 € |        35 € |
| SD Card       |        1 |        7 € |         7 € |
|               |          |            |             |
| Total         |          |            |        42 € |

### Hardware assembly

![Photo of required parts, unboxed](/images/03.jpg?raw=true)

![Photo of optional parts, unboxed](/images/04.jpg?raw=true)

TODO

![Photo of double-sided tape on a drive](/images/05.jpg?raw=true)

![Photo of double-sided tape on the first drive](/images/06.jpg?raw=true)

![Photo of double-sided tape on the second drive](/images/07.jpg?raw=true)

![Photo of the USB hub plugged into all three drives using short USB cables](/images/08.jpg?raw=true)

![Photo of double-sided tape under the USB hub](/images/09.jpg?raw=true)

![Photo of the USB taped onto the top drive](/images/10.jpg?raw=true)

![Photo of the USB taped onto the top drive with the free USB port visible](/images/11.jpg?raw=true)

### Software setup

TODO

## Benchmarks

TODO:
 - compare CD drive power (≤ 2.5 W) and USB power (2.5 W for USB-HP, 4.5 W for USB-HPSS)
 - compare CDA bandwidth with USB bandwith
 - compare CDA bandwidth with RPi FLAC encoding bandwidth and PC FLAC encoding bandwidth

## Contributing and reporting bugs

Contributions are welcome through [GitHub pull requests](https://github.com/Arkanosis/OpenRipStation/pulls).

Please report bugs and feature requests on [GitHub issues](https://github.com/Arkanosis/OpenRipStation/issues).

## License

OpenRipStation is copyright (C) 2022 Jérémie Roquet <jroquet@arkanosis.net> and licensed under the ISC license.
