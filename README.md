# Interactive Four-Stroke Engine Model using Autodesk and Arduino

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Components](#components)
- [Software](#software)
- [Hardware Setup](#hardware-setup)
- [Arduino Code](#arduino-code)
- [Assembly and Working](#assembly-and-working)
- [How to Run](#how-to-run)
- [Future Enhancements](#future-enhancements)
- [Conclusion](#conclusion)

## Introduction
This project presents a digital and physical model of a four-stroke engine, created to understand how internal combustion engines function. The model includes all key engine components, designed using Autodesk, and implemented as a physical model using acrylic sheets, PVC pipes, and other accessible materials.

## Project Overview
The model illustrates the four strokes:
1. **Intake Stroke**
2. **Compression Stroke**
3. **Power Stroke**
4. **Exhaust Stroke**

LEDs light up at each stroke to indicate the ongoing phase, and a DC motor is used to simulate piston movement, while the Arduino Uno handles the control logic.

## Components
### Digital Components:
- **Autodesk Software:** Used for 3D modeling and part design.
- **Parts Designed:**
  - Pistons
  - Supports
  - Cylinder block
  - Crankshaft

### Hardware Components:
- **Acrylic Sheets (for body and structure)**
- **PVC Pipes (for pistons)**
- **LEDs (to indicate strokes)**
- **DC Motor (to rotate pistons)**
- **Relays and Channels**
- **Arduino Uno Board**
- **Wiring and Connectors**

## Software
- **Autodesk** is used to design the engine parts.
- **Arduino IDE** is used to program the control logic.

## Hardware Setup
1. **Structure:** Assemble the frame using acrylic sheets and PVC pipes to mimic the engine's design.
2. **Pistons:** Attach PVC pipes as pistons and link them to a crankshaft driven by a DC motor.
3. **LED Circuit:** Place LEDs at appropriate locations to indicate each stroke. Connect the LEDs to the Arduino via relays.
4. **DC Motor and Pulley System:** Use a DC motor to rotate the pistons in synchronization with the strokes.
5. **Arduino Setup:** Connect the relays and control channels to the Arduino Uno. The Arduino code handles the timing for LED activation and motor control.

## Arduino Code
The code controls the DC motor speed and LED sequences, simulating each stroke of the engine. [Include the Arduino code in this section or link it here.]

## Assembly and Working
1. **3D Model Creation:** Use Autodesk to design engine components.
2. **Frame Assembly:** Construct the frame using acrylic sheets and attach the components.
3. **Circuit Wiring:** Connect the LEDs, motor, and relays to the Arduino.
4. **Arduino Logic:** Upload the code to Arduino and test the system.
5. **Simulation:** When powered on, the motor drives the pistons while LEDs indicate the engine’s strokes.

## How to Run
1. Assemble the hardware as per the instructions above.
2. Upload the provided code to your Arduino Uno using the Arduino IDE.
3. Power on the system to observe the engine's cycles.

## Future Enhancements
- Integrating sensors to measure real-time parameters (like piston position).
- Improving the model’s aesthetics using advanced materials and 3D printing.
- Developing an interactive display panel for educational purposes.

## Conclusion
This interactive four-stroke engine model offers a hands-on way to understand the internal workings of a combustion engine. By blending digital design and physical modeling, it provides an engaging learning experience.

