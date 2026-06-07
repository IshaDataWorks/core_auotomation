# Greenhouse Monitoring System using ESP8266

## Overview

The Greenhouse Monitoring System is an IoT-based solution designed to monitor environmental conditions inside a greenhouse in real time. The system uses an ESP8266 microcontroller to collect data from sensors and transmit it to the Blynk IoT platform for remote monitoring. It helps maintain optimal growing conditions while enhancing safety through gas and fire detection alerts.

## Features

* Real-time temperature and humidity monitoring
* Gas and smoke detection
* Remote monitoring through the Blynk IoT application
* Local display using a 16x2 LCD
* LED and buzzer-based alert system
* Wi-Fi enabled IoT communication
* Continuous environmental monitoring

## Hardware Components

* ESP8266 (NodeMCU)
* DHT11 Temperature & Humidity Sensor
* MQ2 Gas Sensor
* 16x2 LCD Display
* Buzzer
* LED
* Power Supply
* Connecting Wires

## Software & Technologies

* Arduino IDE
* Embedded C / C++
* Blynk IoT Platform
* ESP8266 Wi-Fi Module

## System Architecture

The ESP8266 acts as the central controller of the system. Environmental data is collected using the DHT11 and MQ2 sensors. Sensor readings are displayed locally on the LCD screen and simultaneously transmitted to the Blynk application via Wi-Fi. When abnormal gas levels or potential fire hazards are detected, the system activates a buzzer and LED alert while sending notifications to the user through the Blynk app.

## Working

1. Sensors collect temperature, humidity, and gas data.
2. ESP8266 processes the sensor readings.
3. Data is displayed on the LCD screen.
4. Sensor values are transmitted to the Blynk application through Wi-Fi.
5. If hazardous conditions are detected, the buzzer and LED are activated.
6. Users can remotely monitor greenhouse conditions through the Blynk dashboard.

## Results

* Successfully implemented real-time greenhouse monitoring.
* Enabled remote access to environmental data using the Blynk platform.
* Provided local and remote alert mechanisms for gas and fire hazards.
* Reduced the need for continuous manual monitoring.
* Demonstrated the practical application of IoT in smart agriculture.

## Future Enhancements

* Automated irrigation system
* Automatic ventilation control
* Cloud-based data analytics
* AI-powered environmental prediction
* Solar-powered operation

## Project Images

Add:

* Hardware Setup
* Circuit Diagram
* LCD Display Output
* Blynk Dashboard Screenshots

## Project Video

Upload a demonstration video showing:

* Sensor monitoring
* LCD output
* Blynk dashboard
* Alert system operation

## Author

**Isha Choudhari**
B.Tech Electronics & Telecommunication Engineering
Government College of Engineering, Nagpur
