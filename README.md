This is a fork of the excelent SSD1306Ascii libray.

Changed the directory structure.

Added: clearToCol(uint8_t c) : clear screen up to column

Added: setInverted(bool inverted): invert the output

Changed: print a space when no space is present in the characterset

Unfortunately auto format made a mess of the source  :disappointed:

---

SSD1306Ascii is an unbuffered character only library for small OLED
displays like the Adafruit 1.3" and 0.96" Monochrome displays.

Many low cost OLED displays with SSD1306 controllers are available on ebay.

SSD1306Ascii runs on Arduino AVR boards, Arduino Due and many other
Arduino style boards that have the SPI or Wire library.

The SSD1306Ascii library only requires a few bytes of RAM.

Here is memory use for the SPI "Hello world!" example with
scrolling disabled:

Sketch uses 2,622 bytes (8%) of program storage space.
Maximum is 32,256 bytes.

Global variables use 53 bytes (2%) of dynamic memory, leaving 1,995 
bytes for local variables. Maximum is 2,048 bytes.

This library is still in development so the API and features may
change. The library may have bugs. 

Feedback for future development is welcome.

This is a total rewrite of an earlier version of this library. 
The previous version is located here:

https://code.google.com/p/beta-lib/downloads/list






