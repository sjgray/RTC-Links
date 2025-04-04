RTC Link II Firmware
====================

The Link II+ board supports two different firmware sets in
a 64K EPROM, selectable via the J4 jumper.

The following files are available:

* RTCLINK2.BIN     - Original 8K firmware
* RTCLINK2-MOD.BIN - Modded 8K firmware with alternate power-on message
* RTCLINK2-64K.BIN - Full 64K binary with both sets above.
                     J4: 0=Original, 1=Modded

If you never plan on using a second firmware set you can just burn
either of the first two above to the EPROM and use a jumper wire
to short J4 pin 0 to pin1.
