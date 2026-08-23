# Design and Implementation of an SPI Master-Slave Mode 0 Communication System Using Verilog HDL

This project implements a **Serial Peripheral Interface (SPI) Master-Slave communication system** using **Verilog HDL**. The design follows **SPI Mode 0 (CPOL = 0, CPHA = 0)** and supports full-duplex serial data communication between an SPI Master and Slave.

The project was designed, simulated, and verified using **Xilinx Vivado**. The SPI Master generates the serial clock (SCLK), controls the Chip Select (CS), and transmits data through MOSI, while the Slave receives the transmitted data and returns data through MISO.

## Key Features

* **SPI Master-Slave communication**
* **SPI Mode 0** operation (CPOL = 0, CPHA = 0)
* **Full-duplex** serial communication
* Master-generated **SCLK**
* **MOSI, MISO, SCLK, and CS** signal generation
* **FSM-based** control for SPI transmission
* Configurable **clock divider** for SPI clock generation
* **Verilog HDL RTL** implementation
* Functional simulation and **waveform verification in Vivado**

## Project Verification

The design was tested using a **Verilog testbench** in Vivado. Simulation waveforms were analyzed to verify correct **CS, SCLK, MOSI, and MISO** timing and data transfer according to the SPI Mode 0 protocol.

This project demonstrates practical experience in **RTL design, FSM implementation, serial communication protocols, clock generation, and functional verification using Vivado**.

## Tools & Technologies

* **Verilog HDL**
* **Xilinx Vivado**
* RTL Design
* Finite State Machine (FSM)
* SPI Protocol
* Functional Simulation
