# Smart Dustbin Using Arduino Uno and Bluetooth

## Project Overview

The Smart Dustbin is an Internet of Things (IoT) based project designed to monitor the waste-filling level inside a dustbin. It uses an ultrasonic sensor to measure the distance between the sensor and the waste material.

The collected sensor data is processed by the Arduino Uno and transmitted wirelessly to a mobile device using a Bluetooth module. The Telnet mobile application receives and records the sensor readings, helping users monitor the dustbin's filling level.

## Objectives

- Monitor the waste level inside a dustbin.
- Measure distance using an ultrasonic sensor.
- Establish wireless communication using Bluetooth.
- Receive and record sensor data through a mobile application.
- Demonstrate a simple IoT-based monitoring system.

## Hardware Requirements

| S.No | Component | Purpose |
|---|---|---|
| 1 | Arduino Uno | Main controller |
| 2 | Ultrasonic Sensor | Measures waste-level distance |
| 3 | Bluetooth Module | Wireless communication |
| 4 | Connecting Wires | Hardware connections |
| 5 | Power Supply | Powers the system |

## Software Requirements

- Arduino IDE
- Telnet Mobile Application
- Arduino Programming (C/C++)

## Working Principle

### 1. Arduino Uno
The Arduino Uno acts as the main controller. It receives distance measurements from the ultrasonic sensor and processes the readings.

### 2. Ultrasonic Sensor
The ultrasonic sensor measures the distance between the sensor and the waste inside the dustbin. As the waste level increases, the measured distance decreases.

### 3. Bluetooth Module
The Bluetooth module establishes wireless communication between the Arduino Uno and the mobile device.

### 4. Telnet Mobile Application
The Telnet application receives the sensor readings transmitted through the Bluetooth connection and records the collected data.

## System Workflow

1. The ultrasonic sensor measures the distance inside the dustbin.
2. The Arduino Uno processes the sensor readings.
3. The Bluetooth module transmits the readings wirelessly.
4. The Telnet application receives the transmitted data.
5. The received readings help monitor the waste-filling level.

## Technologies Used

- Internet of Things (IoT)
- Arduino Uno
- Embedded Systems
- Bluetooth Communication
- Ultrasonic Sensing
- Arduino IDE

## Project Features

- Real-time distance measurement.
- Wireless sensor-data transmission.
- Mobile-based monitoring.
- Simple and low-cost prototype.
- Waste-level monitoring.

## Project Limitations

- The system monitors distance readings and does not automatically open or close the dustbin lid.
- Bluetooth communication requires the mobile device to be within the module's communication range.
- The project does not include automatic waste collection or disposal.

## Expected Output

The ultrasonic sensor measures the distance between the sensor and the waste. The Arduino processes the readings and sends them to the mobile application through Bluetooth.

## Future Enhancements

- Add an LED or buzzer alert when the dustbin reaches a predefined filling level.
- Develop a dedicated mobile application.
- Add cloud-based monitoring.
- Support remote monitoring of multiple dustbins.

## Author

**Sana Omkareswar**
