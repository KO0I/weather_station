# Simple Weather Station

## Installation:

Firmware can be installed to Atmega328p via arturo or ino (if using ino,
change file names to *.ino). Alternatively, you can use the Arduino IDE.

## Description  

A collection of weather-station parts and firmware that I want to put together
as part of an amateur weather station. The parts are mostly 3D-printed (links
to the projects are in the 

## Objectives:
* wireless
* lightweight
* waterproof
* easy to replicate/repair

The system will be controlled by an ESP8266 or ATMEGA 328P. 

### Currently intended to track:
* Wind speed      (simple pulses)
* Rainfall        (simple pulses)
* Wind direction  (potentiometer)
* Temperature     (SHT15 w/ quasi-I2C)
* Humidity        (SHT15 w/ quasi-I2C)

### Interested in adding in:

* Lightning detection (antenna and circuit)
* Sunlight exposure sensors (measure power from a few small solar panel nodes?)
* RTLSDR housing+weatherproofing
* Logging data
* Display Results in a web browser

## 

## Acknowledgements

### STLs

#### Wind Vane
  [Wind Vane for Arduino or Pi Weather Station by
micromet](http://www.thingiverse.com/thing:952978)
#### Humidity and Temperature
 [Radiation Shield For Weather Station Temperature/Humidity by
micromet](Radiation Shield For Weather Station Temperature/Humidity)
#### Anemometer and Rain Gauge
 [Weather Station by femoral](Radiation Shield For Weather Station
Temperature/Humidity)

## License

[Creative Commons
Attribution-ShareAlike](https://creativecommons.org/licenses/by-sa/3.0/)
