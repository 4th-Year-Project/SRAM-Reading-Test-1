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

## Todo
 - [ ] Upper limit of the RAM address is still untested
 - [ ] More
