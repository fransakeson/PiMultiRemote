# PiMultiRemote
# Use RaspberryPi as gateway to control all your appliances

Todo: Fix config array to trigger on key instead of looping thorugh the whole thing on each keypress. Stupid stupid.

## My HW setup:
Raspberry Pi with a 38KHz IR tranceiver ($7) controlled by an MX3 2.4G RF Remote Control ($12).
Had a old IR extender lying around which was useful for the signal to reach all the gadgets.

## What I currently control:

**Amplifier to control volume and A/V input (IR).**

**Set-top box (IR).**

**Kodi on a seperate Raspberry Pi, controlled through json calls, thus the kodi-cli helper script.**

The TV itself is basically just a dumb monitor, since the amp and set-top handles everything needed.

Everything except the Pi's is powered through a master/slave power strip, when I turn off the amp, everything else is cut off from power.
