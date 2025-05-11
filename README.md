# Auto Gate System

This repository contains the code for an automated gate system. The gate is controlled using an ultrasonic sensor, a servo motor, LEDs, and a buzzer. The system automatically opens the gate when an object is detected within a certain range and closes it after 5 seconds.

## Features:
- **Automatic Gate Opening:** The gate opens when an object is detected within 15 cm.
- **LED Indicators:** A red LED indicates the gate is closed, and a blue LED indicates the gate is open.
- **Buzzer Feedback:** The buzzer gives periodic feedback when the gate is open.
- **Servo Motor Control:** The servo motor is used to move the gate.

## Code Explanation:

The `auto_gate_system.ino` file contains the logic for operating the gate system:
- **Ultrasonic Sensor:** Measures the distance between the gate and any object. If the object is within 15 cm, the gate opens.
- **Servo Motor:** Opens and closes the gate based on the sensor input.
- **LEDs:** Red LED for the closed gate and Blue LED for the open gate.
- **Buzzer:** Provides feedback when the gate is open.

## Circuit:
- **Trig Pin:** Connected to the ultrasonic sensor's trigger pin.
- **Echo Pin:** Connected to the ultrasonic sensor's echo pin.
- **Servo Motor:** Controls the gate movement.
- **LEDs:** Indicates the gate status.
- **Buzzer:** Provides audio feedback.

AUTHOR: UWAYO Ange Kevine
