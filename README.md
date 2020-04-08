# Object Oriented MIPI RFFE Reference Architecture
This project is an object oriented implementation of the [MIPI RFFE API for PXIe-657x Digital Pattern Instrument](https://forums.ni.com/t5/Example-Programs/MIPI-RFFE-API-for-PXIe-657x-Digital-Pattern-Instrument-Register/ta-p/3728425?profile.language=en) by Kyle_A.

## Devices
Intended for use with National Instruments Digital Pattern Instruments.
- PXIe-6570
- PXIe-6571

## Key Features
1. Parity checks for read commands
2. Dynamic pattern creation and compilation
3. Multi-bus Support

## About
While the underlying architecture of this library is class based, the exported APIs are still linear in nature.
See the [Exports](Exports) folder for VIs intended to be used in applications.

## Examples
A set of examples is provided in the [Examples](Examples) folder.
