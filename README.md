# CONNECTION

Ultrasonic Sensor (HC-SR04):
VCC → 5V on Arduino

GND → GND on Arduino

TRIG → Pin 9 on Arduino

ECHO → Pin 10 on Arduino


Relay Module:

VCC → 5V on Arduino

GND → GND on Arduino

IN → Pin 7 on Arduino

COM and NO (Relay) connected to the light circuit.

# ABOUT PROJECT
IoT-Based Object Detection and Light Control using Arduino, Ultrasonic Sensor, and Relay Module
Project Overview
This project implements an IoT-based system using an Arduino Uno, an ultrasonic sensor, a relay module, and a light. The system detects objects within a specified range using the ultrasonic sensor and controls the blinking of a light through the relay module.

Components Used:
Arduino Uno,
HC-SR04 Ultrasonic Sensor,
Relay Module,
LED Light or Bulb,
Breadboard and Jumper Wires,
External Power Supply for the Light,


How It Works:
The HC-SR04 Ultrasonic Sensor continuously measures the distance of objects in front of it.
If an object is detected within the predefined range (e.g., less than 10 cm), the sensor sends a signal to the Arduino Uno.
The Arduino Uno controls the relay module to blink the connected light.
The light remains off when no object is detected and blinks on detection.


Key Features:
Real-time object detection using the HC-SR04 Ultrasonic Sensor.
Automatic control of a light using a relay module.
Easy to configure detection range for different scenarios.
Simple and effective hardware setup.


Applications:
Automated lighting systems in homes or offices.
Object detection for proximity alerts in warehouses or parking systems.
Energy-saving systems that activate lights only when needed.
Instructions:
Connect the HC-SR04 Ultrasonic Sensor, relay module, and light to the Arduino Uno according to the provided circuit diagram.
Upload the provided Arduino code to your Arduino Uno.
Power the system and test by placing an object within the detection range of the ultrasonic sensor.
The light will blink whenever an object is detected.
