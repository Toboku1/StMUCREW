# Description
This repository is a detailed description of the process to create a muon detection system used to determine the effects of water shielding and frequencies of cosmic particles dependent on the angle of the detector relative to the horizontal
# Contents
  - Downloadable cad files for the 3D printed tower and base used to set the position of the muon detectors will be available
  - Code for a microSD card reader
  - Code for an OLED display
  - Code for an accelerometer
  - Results of the project
  - Common errors along the way and their solutions
# Hardware Requirements
  - MP6050 accelerometer
  - SSD1306 OLED Display
  - Microcontroller*
  - PCB boards
  - 3D printer
  - Cosmic Watch V2 device
  - Soldering iron
* *In this project we used both an arduino and an ESP32 microcontroller. Both work with Arduino IDE and the code provided, but the Arduino nano does not have the ram required to run both the OLED display and the SD card for the computer display. An Arduino UNO is sufficient to run both, but the ESP32 is cheaper and works just as well.
# Software Requirements
  - Arduino IDE
  - Arduino nano*
  - ESP32*
* Either of these microcontrollers can be used in the project, but the ESP32 has more processing power and is capable of running the OLED, the Sim Card, and the Accelerometer at the same time unlike the Arduino Nano, which can only run one of the 3.
