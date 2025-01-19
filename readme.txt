RTC Link Devices
================

http://www.cbmsteve.ca/
http://www.cbmsteve.ca/rtclinks/index.html

This is a project to clone and improve the Richmond Telecommunications ("RTC") Devices.

RTC released several different devices including:

* V-Link for VIC-20
* V-Link "64" for C64
* Link for C64
* Link-II for C64
* Mult-Link for C64

I personally own both a Link and Link-II, which I would like to clone. I have started with
the Link-II as it has the most features of the two. Also, the Link-II uses a single PCB
with components on both sides.


Link-II
-------

This is a single PCB with components on both sides. It was done this way to make the PCB
as small as possible so it could fit inside an AMP connector shell. There are two flyouts
that are connected internally into the C64 to make the Link more "transparent" which means
that IO and ROM are invisible when not in use. The Link-II also seems to work without these
connections but might have conflicts with other hardware or software.

First step was to desolder all the components and scan each side. I then flipped the back-side
scan. Kicad was loaded and a new project created. I then loaded the front side and flipped
back-side as images and then added the components. I added global labels for the busses For the
address and data lines etc. I placed the components in their proper places then traced over the
traces on the images to connect the pins, updating labels where necessary.

Status: The design is complete. I will be ordering PCB's shortly (after the holidays).


Link-II Plus
------------

Once the Link-II was reverse engineered I decided to make a new version but with all components
on the same side making the board easier to build. I replaced the DIP eprom with a PLCC version,
and the resistors with a resistor network in order to save space. I also replaced the Link
edge-connector with a pin header to allow a more common IDC riboon cable.

Status: The design is complete. After the regular Link-II is verified I will make a run of
	Link-II+ boards.

Future
------

I would like to clone the original Link design but it uses a double-pcb design. I think the
original design would be ok for most people.

