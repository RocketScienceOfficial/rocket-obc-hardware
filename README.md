# OBCv1.5

## Overview
Schematics & PCB document for rocket OnBoard Computer version 1.5

## Features
 - High quality sensors:
   - IMUs (accelerometers, gyroscopes & magnetometer)
   - GPS
   - Barometer 
 - Control of four igniters
 - Control & current measure of four servos
 - Ability to connect radio device (for example LoRa)
 - Data logging to flash memory
 - External voltages connectors (VBAT, 5V, 3.3V)

## Renders

![](https://github.com/Filipeak/rocket-obc-hardware/blob/main/OBC%20v1.5/assets/obcrender-removebg-preview.png)![](https://github.com/Filipeak/rocket-obc-hardware/blob/main/OBC%20v1.5/assets/obcrenderback-removebg-preview.png)

## Setup
Project is done on Altium Designer 24.0.1 but it should be fine to run it on other versions

Install Altium Designer, choose your licence and open project

## The Project
The rocket on-board computer project is a comprehensive initiative aimed at developing a sophisticated system to manage and control various aspects of a rocket's operation. 

The project encompasses five main components:
 1. [On-Board Computer](https://github.com/Filipeak/rocket-obc-firmware)
 2. [On-Board Hardware Designs](https://github.com/Filipeak/rocket-obc-hardware)
 3. [Telemetry](https://github.com/Filipeak/rocket-telemetry)
 4. [Estimation & Control Library](https://github.com/Filipeak/rocket-ecl)
 5. [Ground Station](https://github.com/Filipeak/rocket-gcs)