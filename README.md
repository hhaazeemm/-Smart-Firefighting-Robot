# FireFighter Robot

A smart robot project designed to support firefighting teams.  
Equipped with a camera, flame sensor, gas sensor, water pump, and remote control system.  
The robot explores hazardous areas, extinguishes fires, and detects trapped individuals.

## Features
- Fire detection and extinguishing
- Gas leakage detection
- Live video streaming
- Remote-controlled movement
- Obstacle detection

## Components
- ESP32-CAM
- Arduino MEGA
- Flame Sensor
- Gas Sensor (MQ-2 or similar)
- Ultrasonic Sensor
- Water Pump
- Motor Driver
- 4 DC Motors
- Relay Module
- 3x 3.7V Batteries

## Usage
1. Upload the code to Arduino and ESP32-CAM.
2. Power on the robot.
3. Control it via the web interface.
4. It detects fire and moves toward it to extinguish it.
5. Sends alerts if gas is detected.

## Future Work
- Add AI-based object recognition.
- Improve autonomous navigation.
