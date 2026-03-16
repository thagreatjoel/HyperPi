# Seed Pi 🌱

Seed Pi is a small Linux single-board computer built around the RK3308B processor.
This project was created as part of Stasis, a hardware event by Hack Club.

Stasis: https://stasis.hackclub.com

The goal of Seed Pi is to learn how a real computer is built from the processor and RAM all the way to a working Linux system.

![image1](https://raw.githubusercontent.com/thagreatjoel/SeedPi/refs/heads/main/img/seedpi.jpg)


---

## What is Seed Pi?

Seed Pi is a custom SBC designed for:
- learning hardware design
- experimenting with embedded Linux
- building IoT projects
- understanding how computers work internally

The board boots Linux from a microSD card and can be accessed using UART or SSH over WiFi.

---

## Main Features

- RK3308B processor
- DDR3 RAM
- WiFi + Bluetooth (RTL8723DS)
- microSD boot
- USB support
- UART debug interface
- 40-pin GPIO header
- USB-C power input


---

## Hardware

Main components used:

- RK3308B processor
- Samsung K4B4G1646E DDR3 RAM
- RTL8723DS WiFi + Bluetooth
- CH340C USB-UART converter
- AMS1117 regulators
- ETA5050 1.0V regulator
- MicroSD card socket
- USB connectors
- 40-pin GPIO header

---

## Specs

- CPU: Rockchip RK3308B (Quad-core Cortex-A35)
- RAM: DDR3
- Wireless: WiFi + Bluetooth (RTL8723DS)
- Storage: microSD card
- USB: USB Type-A
- Debug: UART (CH340C)
- GPIO: 40-pin header
- Power: USB-C (power only)
- OS: Linux (Armbian / Debian)

---

## Current Status 🟢

The schematic and PCB design are currently in progress. Component placement and routing are being developed in EasyEDA.
