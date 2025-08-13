# Automated Plant Watering System

An **Arduino-based automated plant watering system** that monitors soil moisture and waters plants only when needed — helping you keep your plants healthy with minimal effort.

---

## Features
- **Soil Moisture Monitoring** – Uses a sensor to detect when the soil is dry.
- **Automated Watering** – Activates a pump or valve to water plants automatically.
- **Customizable Threshold** – Adjust the soil moisture threshold to suit different plants.
- **Water Level Monitoring** *(optional)* – Alerts you when the water reservoir is low.
- **Low Power Consumption** – Designed for continuous operation with minimal energy use.

---

## Hardware Requirements
- **Microcontroller** – Arduino Uno/Nano or compatible board
- **Soil Moisture Sensor** – Capacitive or resistive
- **Water Pump / Solenoid Valve**
- **Relay Module / MOSFET** – To control pump or valve
- **Water Tubing**
- **Reservoir** – Bucket, bottle, or tank
- **Jumper Wires & Breadboard** *(optional)*
- **Power Supply** – USB or external DC adapter

---

## Software Requirements
- [Arduino IDE](https://www.arduino.cc/en/software)
- Required libraries *(if applicable, e.g., for sensor or display)*

---

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/mkzafar/Plant-Automation-System.git
   cd Plant-Automation-System
  

## Uploading the Code
1. Open the `.ino` file in **Arduino IDE**.
2. Connect your Arduino to your computer.
3. Select your board and COM port from:
   - `Tools > Board`
   - `Tools > Port`
4. Click **Upload** to send the code to your board.

---

## Configuration
- Adjust **`MOISTURE_THRESHOLD`** in the code to set your desired dryness level.
- Modify **pump runtime** to control how long the pump runs each cycle.

---

## Usage
1. Insert the **soil moisture sensor** into the plant’s soil.
2. Fill the **water reservoir**.
3. Power the system — it will monitor soil moisture and water automatically when needed.

---

## Safety & Notes
- Ensure the **pump’s voltage** matches your power supply.
- Keep **electronics away from water** to prevent damage.
- **Resistive moisture sensors** degrade faster in wet conditions — consider a **capacitive sensor** for better longevity.

---

