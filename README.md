# Overview of ScioSense's GitHub Repositories

This page is intended to give an overview of the available drivers for ScioSense products. ScioSense itself provides
Arduino libraries to enable a quick and easy start with our products. 

In addition, some third-party repositories are listed at the end of this document.
Please note that these projects are not developed by ScioSense and the listing is not an official recommendation.

You can post any issues you have with the drivers on the respective GitHub repository. If you have questions about 
our products themselves, please use the [contact form](https://www.sciosense.com/contact/) on our website.

Dashboard software and Labview drivers can be found in the [download area](https://downloads.sciosense.com/) on our
website. 

## Arduino Libraries
Our Arduino libraries are available directly via the Library Manager in the Arduino IDE or here on GitHub.

The code can be found in the following repositories:

| Product  | Function                                | Bus      | Repository                                                  |
|----------|-----------------------------------------|----------|-------------------------------------------------------------|
| APC1     | All-in-one combo sensor                 | I2C/UART | [APC1_driver](https://github.com/sciosense/APC1_driver)     |
| ENS145   | Metal-Oxide Gas Sensor                  | Analog/(I2C) | [ENS145_driver](https://github.com/sciosense/ENS145_driver)     |
| ENS160   | Metal-Oxide Gas Sensor                  | I2C      | [ENS160_driver](https://github.com/sciosense/ENS160_driver) |
| ENS21x   | Humidity and Temperature                | I2C      | [ens21x-arduino](https://github.com/sciosense/arduino-ens21x) |
| ENS220   | Barometric Pressure and Temperature     | I2C/SPI  | [ens220-arduino](https://github.com/sciosense/arduino-ens220)                                             |
| *CCS811* | Metal-Oxide Gas Sensor (*discontinued*) | I2C      | [CCS811_driver](https://github.com/sciosense/CCS811_driver) |


## Third party repositories provided by our developer community

> :warning: Please note that libraries listed in this section are not maintained
> by ScioSense, and are not supported by ScioSense.

> Note that this list does not claim to be complete. If you would like to have
> your repository listed here, please submit a pull request or file an issue
> containing the GitHub URL. Thanks!

### Sparkfun
- ENS160 Arduino Library: <https://github.com/sparkfun/SparkFun_Indoor_Air_Quality_Sensor-ENS160_Arduino_Library>

### Adafruit
- ENS160 CircuitPython Library: <https://github.com/adafruit/Adafruit_CircuitPython_ENS160>

### From Maarten Pennings 
- ENS210 Arduino library: <https://github.com/maarten-pennings/ENS210>
- CCS811 (*discontinued*) Arduino library: <https://github.com/maarten-pennings/CCS811>
