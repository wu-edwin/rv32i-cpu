# rv32i-cpu

A single-cycle RV32I (32-bit RISC-V) CPU built in Verilog from scratch,
as the anchor project for Summer 2026.

## Goal
By Aug 16, 2026: a working CPU in simulation that executes real RV32I
assembly programs (ADDI, SUB, LW, SW, BEQ, JAL/JALR, branches). Optional
stretch goal: 5-stage pipeline OR FPGA synthesis on a Tang Nano 9K.

## Tools
- iverilog — Verilog compiler + simulator
- GTKWave — waveform viewer
- Verilator — faster simulator + coverage
- gcc — C compiler (for K&R exercises + Python golden model verification)

## Approach
Following Bruno Levy's [FemtoRV "From Blinker to RISC-V"](https://github.com/BrunoLevy/learn-fpga/blob/master/FemtoRV/TUTORIALS/FROM_BLINKER_TO_RISCV/README.md)
tutorial as the spine, diverging in:
- Naming conventions
- Control unit style
- Testbench approach
- Adding extensions not in the tutorial

## Author
Edwin Wu — Georgia Tech Computer Engineering, threads in Computer Hardware
& Emerging Architecture + Cybersecurity.
