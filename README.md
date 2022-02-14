# OpenRipStation (ORS) [![License](https://img.shields.io/badge/license-ISC-blue.svg)](/LICENSE)

**OpenRipStation** (ORS for short) is an open-design audio CD ripping station built with on-the-shelf components and free software.

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
 
Optionaly, you may want to have:

 - An USB extension cable to plug the OpenRipStation to a PC
 - Small USB cables if the ones that come with the CD drives are too long
 - A Raspberry Pi and a 16 GiB SD card for the standalone variant

### Hardware assembly

TODO

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
