# IoT-based-Smart-Parking-System-using-Raspberry-Pi
IoT-Based Smart Parking System Using Raspberry Pi
This project demonstrates an IoT-based smart parking system using a Raspberry Pi. It monitors two parking slots using sensors and displays their status on an LCD screen while publishing real-time data via MQTT for remote monitoring.

Features:
Detects and displays the availability of parking slots using an LCD.
Publishes slot status (Parked or Free) using MQTT for remote monitoring.
Utilizes paho-mqtt for communication and RPi.GPIO for controlling the hardware components.
Components Used:
Raspberry Pi (GPIO control for sensors and LCD).
LCD Display (to show parking status).
IR Sensors (to detect vehicle presence in parking slots).
MQTT Broker (broker.emqx.io) for remote data publishing.
How to Run:
Connect the sensors and LCD as per the GPIO pin setup in the code.
Install the required libraries:
bash
Copy code
pip install paho-mqtt
Run the script:
bash
Copy code
python smart_parking_system.py
Skills Demonstrated:
Python programming for hardware interaction.
IoT communication using MQTT.
GPIO and LCD control using RPi.GPIO and tkinter libraries.
