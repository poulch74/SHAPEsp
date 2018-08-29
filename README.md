# SHAPEsp
> Draft version.

SHAPEsp - Esp8266 based Smart Home Automation Platform

Main goals of this project:
  - One PCB fits in different lowcost cases avialable from AliExpress (cheap blue motorized ball valve, DIN rail case etc).
  - Can be flashed with ESPurna firmware
  - Direct control for DC-motor or Relay via H-bridge TB6612 (can be configured with PWM)
  - Autostop mode for motorized ball valve
  - Keep local time in onboard battery backed DS3231 clock
  - DC power supply 5-12v with mp1584 stepdown for 3V3 power
  - I2C bus for additional functions/sensors (for example BME280 sensor can be connected)
  - some free|configurable ESP8266 Pins available for user (for example Dallas ds1820 can be connected or water sensor(from Ali))
  - additional 3V3 and GND pins
  - nodemcu flash mode in Arduino IDE
  - esp8266 module can be esp-07 esp-12e/f
  

# Fritzing diagram
![SHAPEsp](images/shapesp.png)

# Photo
![SHAPEsp relay](images/relay.jpg)
![SHAPEsp valve](images/valve.jpg)
