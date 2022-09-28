# SFP Access Port
SFP Access Port - SFP Reader, Writer, and Programmer

The SFP Access Port project is an open source effort to create the hardware and associated software capable of reading and writing to the embedded EEPROM found on SFP and SFP+ tranciever modules, as well as other trancievers compliant with the relevant standards.

## Why?
All SFP modules contain an onboard EEPROM - this EEPROM contains information about the modules itself, inluding it's capabilies, compatibilies and vendor origin. The ability to extract this information from trancievers can be beneificial for a number of reason.

SFP modules are frequenetly coded with specific hardware vendors with which it should be considered compatiable - depsite the hardware being identical to other modules. Conversly, some network appliance vendors will lock their devices to only work correctly with specific modules.

This project provides the tools required to read and write this information from compliant modules under certain conditions.

## Components
The below are the current and planned components of the project - they are included as submodules in this repository for convenience
#### sfp-access-port-hardware
All hardware design files can be found in this repository. Any hardware issues should be raised here.

#### sfp-access-port-firmware
Firmware support the above mentioned hardware. The SFP Access Port firmware is written in Rust.

#### sfp-access-port-application
*FUTURE - Work not commenced*
Client application for interfacing with the SFP Access Port hardware.

## Project Goals

Coming Soon!

