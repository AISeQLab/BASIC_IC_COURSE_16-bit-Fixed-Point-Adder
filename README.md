# BASIC_IC_COURSE_16-bit-Fixed-Point-Adder

## Introduction
This project implements a 16-bit fixed-point adder in Verilog and runs on the ZCU102 FPGA board. The fixed-point format is defined as 1-bit sign, 8-bit integer, and 7-bit fractional.

## Overview
The module performs addition between two signed 16-bit fixed-point numbers and outputs the 16-bit result. The fractional precision is preserved, and basic overflow handling is included.

## Design Summary
- Input: two 16-bit signed fixed-point numbers (1 sign, 8 integer, 7 fractional)
- Output: one 16-bit signed fixed-point result
- Target Device: Xilinx ZCU102 FPGA
- Language: Verilog

## How to Use
1. Open the project in Vivado.
2. Synthesize and implement the design for the ZCU102 board.
3. Program the FPGA and run the provided testbench.
4. Observe results in the host PC's terminal using the UART.

## Author
Pham Hoai Luan  
Nara Institute of Science and Technology (NAIST), Japan
