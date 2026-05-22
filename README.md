# Reflow Oven

A custom toaster-oven-based solder reflow oven designed for assembling surface-mount PCB projects. This repository contains the hardware design files, KiCad PCB project, and STM32 firmware source code for a microcontroller-controlled reflow oven.

## Overview

This project converts a standard toaster oven into a controlled solder reflow oven. The goal is to create a repeatable heating system that can follow a solder reflow temperature profile for assembling surface-mount components.

The system is built around a custom PCB and an STM32 microcontroller. The controller reads temperature feedback, drives the oven heating element through a relay/control circuit, and provides user control for starting and monitoring the reflow process.

This project was inspired by the DIY reflow oven concept shown in the Instructables project: [DIY REFLOW OVEN](https://www.instructables.com/DIY-REFLOW-OVEN/). That project demonstrates the general idea of modifying a toaster oven into a solder reflow oven, while this repository focuses on my own STM32-based hardware and PCB implementation.

## Features

- Custom PCB designed in KiCad
- STM32-based embedded controller
- Toaster oven heating control
- Temperature feedback for reflow profile control
- Hardware files for schematic and PCB layout
- STM32CubeIDE project files
- Firmware source code written primarily in C
- Designed to support surface-mount PCB assembly
<img width="1275" height="1002" alt="image" src="https://github.com/user-attachments/assets/4c76bfb0-ead2-42b1-9171-60541e8fe1f5" />
