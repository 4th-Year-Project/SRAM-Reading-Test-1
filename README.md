# SRAM reading test 1

## Description
- Writes SRAM, Reads SRAM and prints this over serial. 
- Starts at 0xFFFF FFFF down to 0x0
- Serial 115200 baud

## Details
- RAM range 0x6000 0000 - 0x006F FFFF
- `#include "xil_io.h" ` Library
	- `Xil_In64(addr)` Reads Specified address
	- `Xil_Out64(addr, value)` Writes to specified address
-  Designed for CMOD A7-35T
-  Vivado and SDK project

## How to use
 - Program FPGA and soft processor using Xilinx SDK
 - Run the program using the Xlinx SDK debugging functions
 - Open device serial port at 115200
 - The data is then read to serial

## Todo
 - [ ] Upper limit of the RAM address is still untested
 - [ ] More
