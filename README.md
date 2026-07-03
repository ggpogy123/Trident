# Trident

A custom, hardware control board featuring a esp32, dual-axis joystick, and three independent SPI displays. 

## Overview
Trident is designed to be a modular, compact interface board. By routing the SPI MOSI, SCK, and LED lines in a daisy chain configuration, the board allows a single ESP32 microcontroller to drive three 2.8 inch TFT LCD screens simultaneously while reading analog inputs from a PS2 style joystick. 

## Visuals
<img width="1588" height="583" alt="image" src="https://github.com/user-attachments/assets/55dacca8-662e-43c9-8364-ef39ac0380ba" />
<img width="1578" height="553" alt="image" src="https://github.com/user-attachments/assets/942f70f7-f32e-4030-b241-de18ee6bf8c5" />
<img width="2126" height="752" alt="image" src="https://github.com/user-attachments/assets/f6cc36db-f557-494c-b62f-6bfd32f60a01" />
<img width="2086" height="732" alt="image" src="https://github.com/user-attachments/assets/311b9be9-1589-4633-90ab-602f06e82c62" />
<img width="1180" height="686" alt="image" src="https://github.com/user-attachments/assets/142c89a4-422d-4323-b80d-3c9cab849693" />





## Hardware Specifications
* **Microcontroller:** ESP32 38-pin Development Board
* **Displays:** 3x 2.8 inch TFT LCDs (ILI9341)
* **Input:** Dual Axis PS2 Analog Joystick Module (KY-023)
* **PCB Specs:** 2-layer FR4, 195.5 x 61.5 mm, 1.6mm thickness

## Key Design Features
* **Wi-Fi Optimization:**  The boundary of the PCB has been cut to ensure that the antenna of the ESP is placed outside the fiberglass. This is done to prevent any kind of interference.
* **Current Handling:** VCC lines are routed with 0.7mm trace widths.
* **Ground Plane:** A copper pour layer has been used to connect all GND points.
