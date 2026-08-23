 # Design-and-Implementation-of-an-SPI-Master-Slave-Mode-0-Communication-System-Using-Verilog-HDL

This project implements a Serial Peripheral Interface (SPI) Master-Slave communication system using Verilog HDL. The design follows SPI Mode 0 (CPOL = 0, CPHA = 0) and supports reliable full-duplex serial data communication between an SPI Master and Slave.

The project was designed, simulated, and verified using Xilinx Vivado. The SPI Master generates the serial clock (SCLK), controls the Chip Select (CS), and transmits data through MOSI, while the Slave receives the transmitted data and returns data through MISO.
