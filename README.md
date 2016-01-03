# BNO055_FRC
<img src="https://learn.adafruit.com/system/assets/assets/000/024/666/medium800/sensors_pinout.jpg" width="300">

A test project to illustrate how to use the BNO055 sensor ([datasheet pdf] (http://www.adafruit.com/datasheets/BST_BNO055_DS000_12.pdf)) with the FRC control system.

This code is a port of the [Adafruit BNO055 arduino library](https://github.com/adafruit/Adafruit_BNO055/blob/master/Adafruit_BNO055.cpp).
At the time of writing, this sensor was available from:
 - $35: [Adafruit](http://www.adafruit.com/product/2472)
 - $35: [digikey](http://www.digikey.com/product-detail/en/2472/1528-1426-ND/5699182)
 - $40: [Amazon](http://www.amazon.com/Adafruit-Absolute-Orientation-Fusion-Breakout/dp/B017PEIGIG) (prime eligible)
 - $21: The Atmel breakout board at [digikey](http://www.digikey.com/product-detail/en/ATBNO055-XPRO/ATBNO055-XPRO-ND/5230918) will likely also work (untested).

##Wiring
The demo code assumes you've wired the sensor to the I2C port on the roboRio, just below the CAN connector. All pins on the roboRio side are on the I2C port.

BNO055 Pin |roboRio Pin
-----------|-----------
Vin        | 3.3V
GND        | GND
SDA        | SDA
SCL        | SCL

Pinouts for the BNO055 sensor can be found [here](https://learn.adafruit.com/adafruit-bno055-absolute-orientation-sensor/pinouts).

##Video Demos
Coming soon.
