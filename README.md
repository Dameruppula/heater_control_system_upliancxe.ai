Smart Heater System:
The Smart Heater System is a prototype embedded system designed to simulate and control a heating device based on environmental temperature. This system is built around simple and cost-effective components,
aiming to offer automated thermal control with essential safety mechanisms, expandability, and real-time feedback. It is an ideal project for learning embedded systems, sensor integration, and basic automation 
control.

Objective: 
The primary goal of the Smart Heater System is to turn a simulated heater ON or OFF automatically based on specific temperature thresholds. This is done using one or more temperature sensors and a
microcontroller that processes the sensor input and controls the heating actuator. Safety, efficiency, and potential for future expansion are the key guiding principles in this project.

Main Components and Their Roles:
NTC Thermistor (Analog Temperature Sensor)
Used to measure the surrounding temperature. This sensor is inexpensive, responsive, and suitable for real-time monitoring. It’s connected to the microcontroller through a voltage divider,
converting resistance variations into voltage levels.

Microcontroller ( Arduino)
Acts as the brain of the system. It receives input from the sensors, processes the data, executes the control logic, and operates the heater and indicators accordingly.

Heater (Simulated Actuator)
A mock or actual heating element that turns on when the temperature falls below a set minimum and turns off when the maximum threshold is exceeded.

LED Indicator
Provides visual feedback on the system state — such as when heating is active or idle.

Buzzer
Offers audible alerts in the event of overheating or system failure, improving safety and responsiveness.

Communication Protocol
The system communicates primarily using UART (Universal Asynchronous Receiver-Transmitter) protocol. UART provides a serial interface for debugging and logging via the Arduino Serial Monitor.
This allows developers to view sensor readings, heater status, and potential error messages in real-time.

Applications
Home automation systems for energy-efficient heating.
Industrial temperature regulation setups.
Safety monitoring in sensitive environments.
