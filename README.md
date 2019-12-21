# octoled

This is a private little script for turning on the WS2801 neopixel strips that light my 3d printer.  You probably don't want it.

Signals used on the rPi:

pin 23 - SCKL
pin 19 - MOSI (SPI 0)
5V
gnd

to set leds:
octoled red green blue
Where arguments are from 0 to 255

Invoke from https://plugins.octoprint.org/plugins/gcodesystemcommands/

author: kevinh@geeksville.com


