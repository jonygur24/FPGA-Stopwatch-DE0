# FPGA-Stopwatch-DE0
Digital stopwatch system implemented in VHDL and schematic on Quartus II for DE0 board

# FPGA Digital Stopwatch – Quartus II + VHDL

This project implements a stopwatch system on an Altera DE0 FPGA development board using both schematic and VHDL components.

## 🛠 Features

- Start/Stop/Reset stopwatch using board switches
- Timing counters for seconds, minutes, and hours
- Seven-segment display encoding logic
- Clock divider to derive 1 Hz tick from system clock
- Simulation files for waveform testing
- Modular design with VHDL files and schematic blocks
- Quartus Megafunctions (LPM) used for arithmetic and decoding

## 📁 Project Files

- `*.vhd` – Custom VHDL modules (HEX encoder, switches, counters)
- `*.bdf` – Main schematic design
- `*.bsf` – Block symbols for components
- `*.qpf / *.qsf` – Project configuration files
- `*.vwf` – Timing waveform files for ModelSim simulation
- `de0_pins.tcl` – Pin assignments for DE0 board

## 🧠 Educational Purpose

This project was created as part of a digital systems lab to demonstrate the use of schematic entry and VHDL in FPGA design.

## 🖼 Preview

<img width="734" alt="image" src="https://github.com/user-attachments/assets/de7105e9-2bc9-4be3-a104-2f63be5106e1" />


---

📎 Developed and tested on Quartus II with Altera DE0 board.
