# Universal-Remote-Control

## Overview
This project focuses on developing an embedded system that utilizes **ATMEGA32** microcontroller and **infrared (IR) sensors** for transmission (TX) and reception (RX). The goal is to create a functional system that can detect and process signals from the IR sensors to trigger specific actions. The project involves both hardware and software components, including the design and development of a custom **PCB** in **Altium Designer** and the implementation of embedded C code to control the system.

## Project Components

### 1. **PCB Design**
   - **Software Used**: Altium Designer
   - **Scope**: Schematic design, layout, and 3D modeling of the PCB to support ATMEGA32 and IR sensors.
   - **Status**: PCB design is completed, with a successful layout and 3D model.
   
### 2. **Embedded Systems Coding**
   - **Microcontroller**: ATMEGA32
   - **Language**: C
   - **Objective**: Write C code to process signals from the IR sensors and control system behavior based on the input.
   - **Current Status**: Ongoing (Currently developing and debugging the embedded code).

### 3. **IR Sensors (TX and RX)**
   - **Transmitter (TX)**: Sends out infrared signals.
   - **Receiver (RX)**: Detects the infrared signals and relays data to the ATMEGA32 for further processing.

## Features
- **Custom PCB**: Designed from scratch using Altium Designer, featuring ATMEGA32 and IR sensors.
- **Efficient Signal Processing**: Embedded software handles real-time signal processing from the IR sensors.
- **Optimized Layout**: The PCB is designed with efficient signal routing and noise minimization.

## Challenges
The primary challenge was the design of the PCB in **Altium Designer**, ensuring accurate schematics, layouts, and 3D models. Now, the focus has shifted to completing the C code for the embedded system, ensuring proper communication between the ATMEGA32 and the IR sensors.

## Next Steps
- Finalize the embedded C code for ATMEGA32.
- Test and debug the system to ensure proper signal detection and response.

## Repository Structure
- `/PCB_Design/`: Contains Altium Designer files, including schematic, layout, and 3D model.
- `/Embedded_Code/`: Contains the C code for ATMEGA32 (Work in progress).
- `/Docs/`: Documentation related to the project.

## License
This project is open-source and available under the [MIT License](LICENSE).

