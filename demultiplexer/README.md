# Verilog Demultiplexer Project

## Overview
This project implements a 1-to-4 Demultiplexer using Verilog HDL.

A Demultiplexer (DEMUX) is a combinational circuit that routes one input signal to one of multiple output lines based on select inputs.

## Features
- Designed using Verilog HDL
- 1 input and 4 outputs
- Select line controlled output selection
- Includes testbench for simulation
- Simulation waveform included

## Module Description

### Inputs
| Signal | Description |
|--------|-------------|
| din | Data input |
| sel | Select input |

### Outputs
| Signal | Description |
|--------|-------------|
| y | 4-bit output |

## Truth Table

| sel | y |
|-----|---|
| 00 | 0001 |
| 01 | 0010 |
| 10 | 0100 |
| 11 | 1000 |

## Tools Used
- Verilog HDL
- Icarus Verilog
- GTKWave

## Simulation

Compile:

