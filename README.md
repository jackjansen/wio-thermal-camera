# wio-thermal-camera

Thermal camera using the [Seeed Wio Terminal](https://www.seeedstudio.com/Wio-Terminal-p-4509.html) and an [AMG8833 8x8 temperature sensor array](https://www.seeedstudio.com/Grove-Infrared-Temperature-Sensor-Array-AMG8833.html).

The code is based on the Seeed example code from [Build a IR Thermal Imaging Camera using Wio Terminal](https://wiki.seeedstudio.com/Wio-Terminal-Thermal-Camera/) with a number of changes and extensions:

- Mirroring of the display is off by default (my use case is not measuring my own temperature but the temperature of an object I'm pointing the camera at).
- Fixed various issues (such as nagative temperatures being treated incorrectly)
- Allow changing the scale with the joystick (left/right for larger/smaller range, up/down to move the range up or down)


