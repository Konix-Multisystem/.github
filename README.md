# [Konix-Multisystem](https://konixmultisystem.co.uk/)

The Konix Multisystem was to be a British made video game console to be released around 1988-1989.

This repository is an archive of everything that has been gathered in the progress of producing an emulation (software and FPGA) and resurrecting sample demos produced by engineers in the late 80's to demonstrate the capabilities of the system.

This repository contains things from the various implementations of the Konix Multisytem :

* Flare One - Slipstream contains a partial emulation of the Flare One hardware
    * Z80 based, with some of the features of the Konix.
    * A lot of the well known demos (TV Cube etc actually come from this machine)
* The 1988 version of the Konix Hardware
    * 8088 cpu, DSP and Blitter close to final
    * Attack Of The Mutant Camels version of the hardware
* The 1989 version (would have been consumer version)
    * 8088 cpu
    * Last Ninja 2 was developed against this
* The later MSU eras of the Konix
    * 80386 cpu
    * Robocod was developed against this

The archive is currently being put together, but once complete should contain :

* Assemblers for Z80 and 8088 versions of the hardware
* Sources for the various samples we managed to obtain
* Sources and releases for the software emulator (Slipstream)
* The Original NetLists, conversion to verilog tools, and FPGA implementations of the 88 hardware (the 89 version will be uploaded but has not been converted to FPGA at this time)

