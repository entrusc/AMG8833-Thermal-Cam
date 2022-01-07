# AMG8833-Thermal-Cam

A simple thermal camera for ESP32 TTGO T-Display module using AMG8833 sensor.

This is a **fork** that incorporates the following changes:
* temperatures are now formatted in a more readable way, and temperatures out of range are marked accordingly
* added a "selection" mode to make it easier to read the temperature of the central point of the sensor (switch modes using button2)
* incorporated fix for negative temperature bug in AMG8833 library

Inspired by (and partially uses code from) examples from https://github.com/adafruit/Adafruit_AMG88xx and https://github.com/sparkfun/SparkFun_GridEYE_Arduino_Library

Original can be found here: https://github.com/smartynov/AMG8833-Thermal-Cam
