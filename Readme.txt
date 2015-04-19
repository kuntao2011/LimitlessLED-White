# LimitlessLED-White
This program is edited for LimitlessLED White which build on the open source code.

Usage: milight ZONE COMMAND [PARAMETER]
The ZONE argument specifies which bulb zone the command refers to."\
Possible values:
  ALL/0 - All zones
  1     - Zone 1
  2     - Zone 2
  3     - Zone 3
  4     - Zone 4
The COMMAND argument specifies the command to be sent to the given bulb zone.
Some commands require a parameter (see below).
Accepted commands:
  ON                 - Turn the bulbs in the given zone on.
  OFF                - Turn the bulbs in the given zone off.
  UP/U               - Turn the bulbs in the given zone brightness up.
  DOWN/D             - Turn the bulbs in the given zone brightnessdown.
  WARMER/W           - Turn the bulbs in the given zone warm white increase.
  COOLER/C           - Turn the bulbs in the given zone cool white increase.
  ONFULL/F           - Turn the bulbs in the given zone full brightness.
  NIGHTLIGHT/N       - Turn the bulbs in the given zone nightlight brightness.

Reference:
  http://iqjar.com/jar/home-automation-using-the-raspberry-pi-to-control-the-lights-in-your-home-over-wi-fi/
  http://pastebin.com/bctT8qBS
  http://www.limitlessled.com/dev/