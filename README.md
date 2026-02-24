# Embedded-Reaction-Timer-Using-ARM-Assembly-STM32-Discovery-Board-

# ARM Assembly Reaction Time Measurement System

## Overview

This project implements a reaction time measurement system using ARM assembly language on the STM32 Discovery Board. The program interfaces directly with hardware components including LEDs and a push-button to measure human reaction time with cycle-level precision.

The system demonstrates low-level programming concepts such as memory-mapped I/O, bitwise operations, hardware configuration, and performance timing.

---

## Project Objective

To build a fully functional reaction timer that:

- Activates LEDs based on randomized delays
- Detects user input via push-button press
- Measures processor cycle counts between stimulus and response
- Converts cycle differences into milliseconds
- Displays measured reaction time

---

## Technical Concepts Demonstrated

- ARM Assembly Programming
- Memory-Mapped I/O
- Bitwise Masking & Logical Operations
- Hardware Register Configuration
- Embedded Systems Development
- Cycle Count Performance Measurement
- Random Number Generation & Delay Logic
- Hardware Interfacing (LEDs & Push Button)

---

## System Behavior

1. The red LED turns on.
2. A randomized delay (1–5 seconds) is generated.
3. The red LED turns off and the green LED turns on.
4. The user presses the blue push-button.
5. The processor measures the cycle difference between stimulus and response.
6. The reaction time is calculated and displayed in milliseconds.
7. The system resets and repeats.

---

## Key Implementation Details

- Random values are masked to 12 bits using bitwise AND operations.
- Delay values are generated within a bounded range.
- Processor cycle counts are sampled before and after button detection.
- Reaction time is computed using clock cycle conversion to milliseconds.

---

## Hardware Used

- STM32 Discovery Board
- On-board LEDs
- Blue push-button
- ARM Cortex-M Processor

---

## Why This Project Matters

Although my primary focus is data analytics, this project demonstrates strong foundational computer science skills including:

- Low-level system understanding
- Performance optimization awareness
- Precise timing measurement
- Hardware-software interaction

These skills reinforce my ability to understand systems deeply, write efficient code, and debug complex technical problems.

---

## Author

Summer Marwany  
