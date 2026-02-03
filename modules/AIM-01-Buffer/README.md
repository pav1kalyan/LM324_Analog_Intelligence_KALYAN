# AIM-01 – Sensor Buffer Module

## Overview
A quad-channel voltage buffer using the LM324 op-amp to isolate analog
sensors from microcontroller ADC inputs.

## Problem Statement
Directly connecting sensors to microcontroller ADC pins can result in
signal loading, noise, and unstable readings.

## Hardware Solution
Each LM324 op-amp is configured as a voltage follower, providing:
- High input impedance
- Low output impedance
- Stable, repeatable sensor readings

## Development Status
⬜ Schematic design  
⬜ PCB layout  
⬜ Fabrication  
⬜ Assembly  
⬜ Testing
