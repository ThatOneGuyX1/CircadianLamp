# Circadian Lamp

## Overview
The Circadian Lamp project aims to create a smart lighting system that mimics natural light patterns and help user wake up the time they want.
## Breakdown of Different Systems
### 1. Lighting Control System
The lighting control system manages the intensity and color temperature of the LEDs to simulate natural daylight.

### 2. Sensor System
The sensor system includes light sensors and possibly other environmental sensors to adjust the lighting based on ambient conditions.

### 3. Power Management System
The power management system ensures efficient power delivery to the LEDs and other components.

### 4. User Interface
The user interface allows users to control the lamp settings manually or set schedules.

## Hardware BOM
| Component Name | Component Item on PCB | Price | Link |
|----------------|------------------------|-------|------|
| LED Driver     | U1                     | $5.00 | [Link](http://example.com) |
| Light Sensor   | U2                     | $2.50 | [Link](http://example.com) |
| Microcontroller| U3                     | $10.00| [Link](http://example.com) |
| Power Supply   | U4                     | $8.00 | [Link](http://example.com) |
| PCB            | -                      | $15.00| [Link](http://example.com) |

## Major Revisions
### V 1.0.0
The orginal this includes using a RasPi Pico to handle the logic, a basic PWM amplifer and high side switch using MOSFET transitors. It is not powered by USB-C PD but by an external source. 