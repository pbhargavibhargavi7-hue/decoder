# 2-to-4 Decoder using Verilog

## Project Overview

A 2-to-4 Decoder is a combinational logic circuit that converts a 2-bit binary input into one of four output lines. At any time, only one output is HIGH (1), corresponding to the binary input.

## Inputs

- A (MSB)
- B (LSB)

## Outputs

- Y0
- Y1
- Y2
- Y3

## Truth Table

| A | B | Y0 | Y1 | Y2 | Y3 |
|---|---|----|----|----|----|
| 0 | 0 | 1 | 0 | 0 | 0 |
| 0 | 1 | 0 | 1 | 0 | 0 |
| 1 | 0 | 0 | 0 | 1 | 0 |
| 1 | 1 | 0 | 0 | 0 | 1 |

## Boolean Equations

Y0 = ~A & ~B

Y1 = ~A & B

Y2 = A & ~B

Y3 = A & B

## Files Included

- decoder_2to4.v – Verilog design
- decoder_2to4_tb.v – Testbench
- simulation_result.png – Simulation waveform
- README.md – Project documentation

## Software Used

- ModelSim
- Xilinx Vivado
- Icarus Verilog
- GTKWave

## How to Run

1. Compile the Verilog files.
2. Run the testbench.
3. Open the waveform.
4. Verify the outputs using the truth table.

## Author

Bhargavi
