#Adafruit SPI FRAM Driver #

This driver is for the Adafruit SPI FRAM Breakout
    ------> http://www.adafruit.com/products/1897

## About this Driver ##

These modules use SPI to communicate, 4 pins are required to  
interface

Adafruit invests time and resources providing this open source code, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Written by Kevin (KTOWN) Townsend for Adafruit Industries.
BSD license, check license.txt for more information
All text above must be included in any redistribution

To download. click the ZIP button in the top bar, and check this tutorial
for instructions on how to install: 
http://learn.adafruit.com/adafruit-all-about-arduino-libraries-install-use
<!-- START COMPATIBILITY TABLE -->

## Compatibility

MCU               | Tested Works | Doesn't Work | Not Tested  | Notes
----------------- | :----------: | :----------: | :---------: | -----
Atmega328 @ 16MHz |      X       |             |            | 
Atmega328 @ 12MHz |      X       |             |            | 
Atmega32u4 @ 16MHz |      X       |             |            | 
Atmega32u4 @ 8MHz |      X       |             |            | 
ESP8266           |      X       |             |            | 
Atmega2560 @ 16MHz |      X       |             |            | 
ATSAM3X8E         |      X       |             |            | 
ATSAM21D          |             |      X       |            | Works but example needs added code.
ATtiny85 @ 16MHz  |             |             |     X       | 
ATtiny85 @ 8MHz   |             |             |     X       | 

  * ATmega328 @ 16MHz : Arduino UNO, Adafruit Pro Trinket 5V, Adafruit Metro 328, Adafruit Metro Mini
  * ATmega328 @ 12MHz : Adafruit Pro Trinket 3V
  * ATmega32u4 @ 16MHz : Arduino Leonardo, Arduino Micro, Arduino Yun, Teensy 2.0
  * ATmega32u4 @ 8MHz : Adafruit Flora, Bluefruit Micro
  * ESP8266 : Adafruit Huzzah
  * ATmega2560 @ 16MHz : Arduino Mega
  * ATSAM3X8E : Arduino Due
  * ATSAM21D : Arduino Zero, M0 Pro
  * ATtiny85 @ 16MHz : Adafruit Trinket 5V
  * ATtiny85 @ 8MHz : Adafruit Gemma, Arduino Gemma, Adafruit Trinket 3V

<!-- END COMPATIBILITY TABLE -->
