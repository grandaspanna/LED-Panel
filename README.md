# LED Panel
A fancy pants LED panel, featuring a row of addressable LEDs and some backlight ones

There are a total of 34 addressable LEDs:
<li>28 along the bottom (LEDs 0-27)</li>
<li>6 in the background (LEDs 28-33)</li>

The bottom LEDs are designed to shine up and through an engraved piece of clear acrylic, highlighting whatever is engraved.

The code has been developed for the AVR DA32 microcontrollers, leveraging SpenceKonde's DX core and as shown, uses the WS2812FX library for animating the LEDs.

The panel has an onboard CH340 USB adapter to allow UPDI programming via a standard micro USB cable. Depending on the host IDE operating system, a driver may be required.
