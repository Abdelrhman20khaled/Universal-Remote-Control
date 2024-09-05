# Universal-Remote-Control

## Overview
Me and my partner are working on a **Universal Remote Control**. This remote control is programmable and capable of learning and programming other remotes. We have designed 4 different remotes, but the project is scalable based on the vendor's requirements. The system uses **ATMEGA32** microcontroller and **infrared (IR) sensors** for communication between remotes. The project involves both hardware and software, including the design and development of a custom **PCB** in **Altium Designer** and the implementation of embedded C code.

## Project Components

### 1. **PCB Design**
   - **Software Used**: Altium Designer
   - **Scope**: Schematic design, layout, and 3D modeling of the PCB to support ATMEGA32 and IR sensors.
   - **Status**: PCB design is completed, with a successful layout and 3D model.
      ### PCB Design Images

<table>
  <tr>
    <td><img src="Final Schematic.jpg" width="400"/></td>
    <td><img src="Final Layout.jpg" width="400"/></td>
  </tr>
  <tr>
    <td><img src="Non Signal Layer.jpg" width="400"/></td>
    <td><img src="Final PCB" width="200"/></td>
  </tr>
</table>

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

## License
This project is Open-Source.

