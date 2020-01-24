## Adafruit MLX90640 IR Thermal Camera Breakout PCB

<a href="http://www.adafruit.com/products/4407"><img src="assets/4407.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a><br/>
<a href="http://www.adafruit.com/products/4469"><img src="assets/4469.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit MLX90640 IR Thermal Camera Breakout. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4407
* https://www.adafruit.com/product/4469

### Description

You can now add affordable heat-vision to your project and with an Adafruit MLX90640 Thermal Camera Breakout. This sensor contains a 24x32 array of IR thermal sensors. When connected to your microcontroller (or Raspberry Pi) it will return an array of 768 individual infrared temperature readings over I2C. It's like those fancy thermal cameras, but compact and simple enough for easy integration.

One version has a narrow 55°x35° field of view, and we also have a version with a wider 110°x70° field of view

This part will measure temperatures ranging from -40°C to 300°C with an accuracy of +- 2°C (in the 0-100°C range). With a maximum frame rate of 16 Hz (the theoretical limit is 32Hz but we were not able to practically achieve it), It's perfect for creating your own human detector or mini thermal camera. We have code for using this sensor on an Arduino or compatible (the sensor communicates over I2C) or on a Raspberry Pi with Python. If using an Arduino-compatible, you'll need a processor with at least 20KB RAM - a SAMD21 (M0) or SAMD51 (M4) chipset will do nicely. On the Pi, you can even perform interpolation processing with help from the SciPy python library and get some pretty nice results!

This sensor reads the data twice per frame, in a checker-board pattern, so it's normal to see a checker-board dither effect when moving the sensor around - the effect isn't noticeable when things move slowly.

To make it easy to use, we hand-soldered it on a breakout board with a 3.3V regulator and level shifting. So you can use it with any 3V or 5V microcontroller or computer. We've even included SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Just plug-n-play with any of our STEMMA QT (JST SH) cables.

Even better - We've done all the hard work here, with example code and supporting software libraries to get you up in running in just a few lines of Arduino or Python code

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
