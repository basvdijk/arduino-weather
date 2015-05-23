# arduino-weather
Weather station using Arduino

## Files
* arduino-weather-board.jpg - overview picture
* arduino-weather-wiring.png - schematic overview of wires
* arduino-weather.fzz - source file for schematic overview in made in Fritzing (http://fritzing.org/)
* arduino-weather.ino - source file for Arduino
* README.md - this file

## Resources
[![Arduino Weather](http://img.youtube.com/vi/tskHVZVp7Ss/0.jpg)](https://www.youtube.com/watch?v=tskHVZVp7Ss&list=PLx8GfAxNN_auGBR6LYJm67gwEL8KkZsHh&index=1)

## Parts used

* http://www.hobbyelectronica.nl/product/128x64-oled-geel-blauw-i2c/
* http://www.hobbyelectronica.nl/product/dht22/
* http://www.hobbyelectronica.nl/product/regendruppel-meter/
* http://www.hobbyelectronica.nl/product/breadbord-jumper-wiresdraden/
* http://www.hobbyelectronica.nl/product/breadboard-830-insteekpunten/
* http://www.hobbyelectronica.nl/product/arduino-uno-rev3/


### Oled screen
http://www.hobbyelectronica.nl/product/128x64-oled-geel-blauw-i2c/
Was not as expected a screen with yellow and blue pixels. It turned out the first 20px were yellow and the others were blue. The shop offers two libraries. I used https://code.google.com/p/u8glib/

The ordered item is probably the same as http://www.ebay.nl/itm/White-0-96-IIC-I2C-128X64-OLED-LCD-Display-Module-Arduino-STM32-AVR-51-M45-/291216700457?pt=LH_DefaultDomain_0&hash=item43cdde3429
3,25 EUR

### Humidity / temperature sensor
http://www.hobbyelectronica.nl/product/dht22/
Worked as expected using the library from https://github.com/markruys/arduino-DHT

The ordered item is probably the same as
http://www.ebay.nl/itm/AM2302-DHT22-Digital-Temperature-and-Humidity-Sensor-module-for-Arduino-/331561936186?pt=LH_DefaultDomain_0&hash=item4d32a1a53a
1,39 EUR

### Water sensor
http://www.hobbyelectronica.nl/product/regendruppel-meter/
Not quite the sensor I expected. It detects water or no water, but is not accurate on the amount of water on the sensor.
