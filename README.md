# PIC18F4580 – LED Interfacing

## Project Overview
This project demonstrates sequential control of three LEDs using the PIC18F4580 microcontroller and Embedded C.

## Hardware and Software
- **Microcontroller:** PIC18F4580
- **Programming language:** Embedded C
- **IDE:** MPLAB IDE
- **Simulation:** Proteus Design Suite

## GPIO Configuration
- RB1, RB2 and RB3 are configured as output pins using TRISB.
- PORTB is used to control the LED outputs.
- Software delays are used to control the timing of the sequence.

## Files
- `3_LED.c` — LED control program.

## Learning Outcomes
- GPIO input/output configuration
- PORT and TRIS register usage
- Software delay implementation
- Microcontroller programming and simulation


## Proteus Simulation

The circuit below shows the PIC18F4580 interfaced with three LEDs.

![PIC18F4580 Three LED Simulation](Screenshot%202026-10-15%20195257.png)
