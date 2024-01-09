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
| APC1     | Air Purification Combo Sensor           | UART/~~I2C~~ | [apc1-arduino](https://github.com/sciosense/apc1-arduino)     |
| ENS16x   | Metal-Oxide Gas Sensor                  | I2C      | [ens16x-arduino](https://github.com/sciosense/ens16x-arduino) |
| ENS21x   | Humidity and Temperature                | I2C      | [ens21x-arduino](https://github.com/sciosense/ens21x-arduino) |
| ENS220   | Barometric Pressure and Temperature     | I2C/SPI  | [ens220-arduino](https://github.com/sciosense/ens220-arduino)                                             |

## STM32 code examples
Example for the STM32 microcontroler, to familiarize with our products.

The code can be found in the following repositories:

| Product  | Function                                | Bus      | Repository                                                  |
|----------|-----------------------------------------|----------|-------------------------------------------------------------|
| AS6031   | Ultrasonic Flow Converter               | SPI      | [as6031-sample-code](https://github.com/sciosense/as6031-sample-code)     |
| PCAP04   | Capacitance to Digital Converter        | I2C/SPI  | [pcap04-sample-code](https://github.com/sciosense/pcap04-sample-code)     |

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

### From Dave Nadler
- ENS210 1-wire software stack (DS2485-(1-Wire bus)-DS28E18-ENS210): <https://github.com/DRNadler/1Wire>
