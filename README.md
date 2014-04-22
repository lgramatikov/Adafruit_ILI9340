Adafruit_ILI9340 port for Spark Core
================

This is a port of Adafruit_ILI9340 library compatible with Spark Core devices.

Original library is available at https://github.com/adafruit/Adafruit_ILI9340. 

I've only removed AVR specific parts, support for software SPI and some small things like CLEAR_BIT/SET_BIT (these cause warnings in Spark.io IDE). 

Works on my machine using 2.2" screen from www.electrodragon.com/product/eds-tft-lcd-lcm-spi-interface-variable1-82-2.

There is another library for Spark Core devices available at https://github.com/lbarrosoneto/Adafruit_TFT. It might also work with these screens.
