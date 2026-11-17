# USB Interface firmware

Releases of the **USB Interface** firmware for the [DMX Core Pico 2](https://dmxcore.com/pico),
beside its Re-Mapper firmware. With it the board is a two-port USB DMX interface:

- the Enttec DMX USB Pro serial protocol, with the DMXking two-port extensions;
- DMX output on both ports, DMX input on port A;
- RDM on port A for lighting software (for example OLA), and on both ports for the
  DMX Core configuration tools.

Download the `.uf2` from [Releases](../../releases).

## Install or update

1. Hold BOOTSEL while plugging the board into USB (or, from this firmware, send label 1
   or run `picotool reboot -u`). The RPI-RP2 drive appears.
2. Copy `dmxcore-pico2-usb-interface-<version>.uf2` onto it. The board restarts with the
   new firmware.

To go back to the Re-Mapper, copy its `.uf2` the same way.

## Issues

Report problems in [Issues](../../issues), with the version (shown by the DMX Core
configuration tools) and what you were doing.
