# 8085 Memory and I/O Interfacing

This repository contains a course project for the 8085 Microprocessor and Systems Interfacing course.
The project demonstrates memory and I/O interfacing for an 8085 microprocessor system using EPROM, RAM, address decoding, input/output decoding, and peripheral interfacing.

# Project Overview

The system is based on the 8085 microprocessor and includes:

* 8085 microprocessor
* Address latch
* Address decoder
* Two 8K EPROM chips
* Two 4K RAM chips
* Memory-mapped input port
* Peripheral-mapped seven-segment display
* I/O decoder
* Clock circuit
* Reset circuit
* Address bus
* Data bus
* Control signals

# Project Diagrams

# System Block Diagram (block_diagram.png)

The following diagram shows the overall system architecture, including the 8085 microprocessor, address bus, data bus, memory chips, I/O decoder, input port, and seven-segment display.

# Schematic Diagram (schematic_diagram.png)

The following schematic shows the circuit implementation of the 8085 memory and I/O interfacing system.

# Memory Map

The project uses two 8K EPROM chips and two 4K RAM chips.

Device	Size	Address Range
EPROM 1	8K	8000H - 9FFFH
EPROM 2	8K	A000H - BFFFH
RAM 1	4K	D000H - DFFFH
RAM 2	4K	F000H - FFFFH

The full memory map document is available here:

# Memory Map Document

# Project Structure
```text
8085-memory-io-interfacing/
├── images/
│   ├── block_diagram.png
│   └── schematic_diagram.png
├── docs/
│   └── memory_map.docx
└── README.md
```
# Course Information

Course: Microprocessor and Systems Interfacing
Project Type: Course Project
Topic: 8085 Memory and I/O Interfacing

Group Members

* Osama Rafat Shawabkeh
* Zaid Adnan Qabaja
* Almotasembelah Yousef Shehada
* Bashar Abdullah Maree

Tools Used

* EasyEDA for schematic design
* Microsoft Word for memory map documentation
* GitHub for project documentation and sharing

Author / Notes

This project was completed as part of a microprocessor systems interfacing course project.
