RTC-Link II Clone  Reverse Engineered by Steve J. Gray
=================

This is a clone of the RTC-Link II IEEE Cartridge for the Commodore C64.
It also enhances C64 BASIC by adding the extra disk commands of 
Commodore BASIC V4, as well as adding a full machine-language monitor.

The cartridge is a small and simple IEEE interface using a single PIA
chip. To keep the device small it packs in the chip on both sides of the
PCB and is able to be mounted inside an AMP connector shell.

KICAD was used to create a PCB that is very similar to the original and
mounts the components on both sides. I have also created a "plus" version
of the design that retains the same pcb size but with components on one
side, using a PLCC EPROM and resistor pack to reduce the component
footprints. It can also be found on this GitHub repository.

Pictures/info can be found at: http://www.cbmsteve.ca/rtclinks/
The GitHub repository is here: https://github.com/sjgray/RTC-Links

History
-------

V1.0 - 2023-12-04 Initial design prototype. Not tested.
V1.1 - 2025-04-04 Fix for R9. To be tested.
