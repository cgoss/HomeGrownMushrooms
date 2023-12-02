# HomeGrownMushrooms
This is a repository and knowledge base of articles and other tools to document my journey into growing mushrooms at home.


## Table of Contents

- [General](#general)
- [Articles](#articles)
- [Mushroom Types](#mushrooms)
- [Recepies](#recepies)
- [Automation](#automation)
- [Contact](#contact)

## General

### Environment

#### Temperature

#### Moisture

#### Light


### Cultivation

### Harvesting

### Spores

### Sourceing

## Articles

Below is a list of articles that describe all things related to growing mushrooms at home. 


## Recepies



## Automation

### Environment Monitoring
The proper environment for growing mushrooms is important, the proper temperature moisture and growing medium are essential for growth.

### Grow Sensor
The grow sensor is a project using a ESP8266 wemos D1 IoT device that has addon development boards and sensors that are reported to a central service. These modules include DHT Sensors solid state relays for controling water pumps and lights.

#### Sensor Components

[Wemos D1 Mini ESP8266] (https://www.amazon.ca/CANADUINO-WEMOS-ESP8266-Wi-Fi-Module/dp/B07B2JVPKX)
[Wemos DHT11 Shield ] (https://www.amazon.ca/Single-Bus-Digital-Temperature-Humidity-Matching/dp/B07KJBGZLS)
[Wemos D1 Relay] (https://www.amazon.ca/CANADUINO-WEMOS-Shield-Internet-Things/dp/B07CQ831ST)

#### Software Requirements

Arduino IDE  
[Wemos Borads for Arduino IDE] https://arduino.esp8266.com/stable/package_esp8266com_index.json
[Wemos Driver] (https://www.wemos.cc/en/latest/ch340_driver.html?highlight=drivers#ch340-driver)


#### Sketch Dependencies
[Adafruit DHT Sensor Library] (https://github.com/adafruit/DHT-sensor-library/tree/master)
[WiFi Module] 

[Reference 1] (https://randomnerdtutorials.com/esp8266-nodemcu-http-get-post-arduino/#http-post)
[Reference 2] (https://mischianti.org/how-to-create-a-rest-server-on-esp8266-and-esp32-startup-part-1/)
[Wifi Access point Reference] (https://microdigisoft.com/wemos-d1-wifi-esp8266-setting-up-wifi-as-server/)



!TODO: Add code for controlling the sensor

#### Sensor Features
Listed below are the features for the sensors. 

- Host web interface to display current temp and moisture
- Record Temperature and Moisture
- Push Temperature and Moisture to logging database
- Update configuration for logging location



### GrowPi
The GrowPi project leverages a rasbperry pi or other computer to monitor the growing environment. The project is buit in python and has the following features. 

- Temperature monitoring and tracking
- Light Monitoring and tracking
- Moisture and Humidity monitoring and tracking
- Threshold Alerting
- Host web service for recieving temperature data
- Push configuration to sensor


