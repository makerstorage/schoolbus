---
layout: archive
sidebar:
  nav: "hw"
---

{% include base_path %}

<center>
<h1><font face ="Acme">Sensor Board </font></h1>

<img src="/../images/sensorboard.jpg" alt="SchoolBus hardware" >

</center>

The aim of this board is to get information from outside world. According to Whatis.com "A sensor is a device that detects and responds to some type of input from the physical environment. The specific input could be light, heat, motion, moisture, pressure, or any one of a great number of other environmental phenomena."

In SchoolBus Sensor board we have 3 different sensors. These are;

* MPL3115A2 Altitude/Pressure Sensor
* HTU21D Temperature and Humidity Sensor
* TSL2561 Luminosity Sensor

Lets take a close look at these sensors.


#### MPL3115A2 Altitude/Pressure Sensor

The MPL3115A2 is a MEMS pressure sensor that provides altitude data to within 30cm. This high tech sebsor outputs are digitized by a high resolution 24-bit Analog to Digital Converter and transmitted over I2C. Pressure output can be resolved with output in fractions of a Pascal, and Altitude can be resolved in fractions of a meter. No calibration reading and calculating required. The device also provides 12-bit temperature measurements in degrees Celsius. Wow! what a great sensor.

#### HTU21D Temperature and Humidity Sensor

The HTU21D is a easy to use, highly accurate, digital humidity sensor. All you need is two lines for I2C communication and you’ll have relative humidity readings in %2 accuracy and also very accurate temperature readings as a bonus in accuracy of ±0.3C! But please keep in mind that This sensor operates from 0 to 100% humidity but it isn’t recommended for harsh environments where it could come in contact with water (such as rain).

#### TSL2561 Luminosity Sensor

The TSL2561 Sensor is a sophisticated light sensor which has a flat response across most of the visible spectrum. TSL2561 measures both infrared and visible light to better approximate the response of the human eye. TSL2561  soaks up light for a predetermined amount of time. It is capable of measuring both small and large amounts of light by changing the integration time.

The TSL2561 is capable of measuring light ranges from 0.1 - 40k+ Lux easily. Additionally, the TSL12561 contains two integrating analog-to-digital converters (ADC) that integrate currents from two photodiodes, simultaneously. 

### Sensor Board Components 


![sensor_board](/../images/sensor_component.png)


### Sensor Board Schematics



![sensor schematics](/../images/sensor_image.png)

