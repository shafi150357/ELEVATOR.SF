# safe elevator
# Smart Elevator Safety System

## Project Overview
The Smart Elevator Safety System is an Arduino-based prototype designed to monitor environmental conditions around an outdoor elevator. It uses sensors to detect light, temperature, humidity, and smoke.

The system automatically controls an indicator light, monitors temperature, activates a cooling fan, and triggers an alarm when smoke is detected.

## Objectives
- Detect darkness using an LDR sensor.
- Monitor temperature and humidity using a DHT sensor.
- Detect smoke using a smoke sensor.
- Activate a fan when the temperature becomes too high.
- Trigger a buzzer and warning LED when smoke is detected.
- Learn Arduino programming and electronic circuit design.

## Components
1. Arduino Uno
2. LDR sensor
3. DHT11 temperature and humidity sensor
4. MQ-2 smoke sensor
5. LEDs and 220-ohm resistors
6. Active buzzer
7. DC fan
8. NPN transistor and flyback diode for fan control
9. 10 kΩ resistor
10. Breadboard and jumper wires

## How It Works
- **LDR sensor:** Detects darkness and switches on the indicator light.
- **DHT11 sensor:** Measures temperature and humidity.
- **Cooling fan:** Turns on when the temperature reaches the configured threshold.
- **Smoke sensor:** Detects smoke or certain gases and activates the alarm.
- **LED indicators:** Show the system's status.

## Applications
- Arduino and embedded-systems education
- Environmental monitoring demonstrations
- Sensor-based automation projects
- Prototype safety monitoring

## Safety Note
This project is an educational prototype only. It is not a certified elevator safety system and must not control a real elevator's movement, doors, brakes, or emergency systems. Use certified equipment for real-world safety applications.

## Future Improvements
- Add an LCD to display sensor readings.
- Add wireless notifications.
- Improve sensor calibration.
- Use a weatherproof enclosure for outdoor installation.
- Add fault detection and backup power monitoring.

## Author
Ineza Shafi  
Computer System and Architecture (CSA) Student
