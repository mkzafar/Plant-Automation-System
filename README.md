Automated Plant Watering System

An Arduino-based automated plant watering system that monitors soil moisture and waters plants only when needed — helping you keep your plants healthy with minimal effort.

Features

Soil Moisture Monitoring – Uses a sensor to detect when the soil is dry.
Automated Watering – Activates a pump or valve to water plants automatically.
Customizable Threshold – Adjust the soil moisture threshold to suit different plants.
Water Level Monitoring (optional) – Alerts you when the water reservoir is low.
Low Power Consumption – Designed for continuous operation with minimal energy use.

Hardware Requirements

Microcontroller: Arduino Uno/Nano or compatible board
Soil Moisture Sensor (capacitive or resistive)
Water Pump / Solenoid Valve
Relay Module / MOSFET (to control pump or valve)
Water Tubing
Reservoir (bucket, bottle, or tank)
Jumper Wires & Breadboard (optional)
Power Supply (USB or external DC adapter)
Software Requirements

Arduino IDE
Required libraries (if applicable, e.g., for sensor or display)

Installation

Clone this repository:

git clone https://github.com/mkzafar/automated-plant-watering-system.git
cd automated-plant-watering-system
Open the .ino file in Arduino IDE.
Connect your Arduino to your computer.
Select your board & COM port from Tools > Board and Tools > Port.
Upload the code to your board.

⚙Configuration

Adjust the MOISTURE_THRESHOLD value in the code to set your desired dryness level.
Set the pump runtime to control how long it waters each cycle.

Usage

Place the soil moisture sensor into the plant’s soil.
Fill the water reservoir.
Power the system — it will monitor soil moisture and water when needed.

Safety & Notes

Ensure the pump’s voltage matches your power supply.
Keep electronics away from water to avoid damage.
If using a resistive moisture sensor, expect it to degrade faster in wet conditions — consider a capacitive sensor for longevity.
