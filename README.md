Seed Pi

Seed Pi is a custom single-board computer (SBC) designed for learning hardware design and embedded Linux. The board is built around the Rockchip RK3308B processor and is intended for IoT projects, experimentation, and understanding how a Linux-based computer works at the hardware level. ![image1](https://raw.githubusercontent.com/thagreatjoel/SeedPi/refs/heads/main/img/seedpi.jpg)

Overview

Seed Pi is a small Linux SBC created as a personal hardware project. The goal of this project is to design a complete computer from scratch, starting from the processor and building the entire system including memory, power regulation, wireless connectivity, and peripheral interfaces.

The board is designed to boot Linux from a microSD card and can be accessed through UART for debugging or through WiFi using SSH once the system is running.

Features

- Rockchip RK3308B processor
- DDR3 RAM
- Realtek RTL8723DS WiFi + Bluetooth
- MicroSD card boot
- USB connectivity
- UART debug interface
- 40-pin GPIO header for sensors and peripherals
- Power-only USB-C input
- Linux support

Hardware

Main components used in the design:

- RK3308B processor
- Samsung K4B4G1646E DDR3 memory
- RTL8723DS WiFi + Bluetooth module
- CH340C USB-UART converter
- AMS1117 voltage regulators
- ETA5050 1.0V regulator
- MicroSD card socket
- USB connectors
- GPIO expansion header

Accessing the Board

Seed Pi can be accessed in two main ways.

UART Console
Used during the first boot and for debugging the system.

SSH
Once Linux is running and WiFi is connected, the board can be accessed over the network using SSH.

Software

The board is designed to run Linux distributions such as:

- Armbian
- Debian-based systems
- Custom embedded Linux builds

Project Goals

- Learn SoC hardware design
- Understand DDR routing and high-speed PCB layout
- Build a custom Linux SBC
- Create a flexible platform for IoT projects

Current Status

The schematic and PCB design are currently in progress. Component placement and routing are being developed in EasyEDA.

Future Plans

- Finish PCB routing
- Manufacture the board
- Boot Linux on the hardware
- Test WiFi, USB, and GPIO
- Build IoT applications using the board

License

This project is open for learning and experimentation.
