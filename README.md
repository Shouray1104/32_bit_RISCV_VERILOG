# 32_bit_RISCV_VERILOG
A Verilog-based single-cycle RISC-V processor implementing the RV32I instruction set. Features include ALU, control unit, register file, and memory modules. Designed for educational purposes to demonstrate instruction fetch, decode, execute, memory access, and write-back in one cycle.

🧠 RISC-V Single-Cycle Processor
This project is a Verilog-based implementation of a single-cycle RISC-V processor, designed as part of a Computer Architecture and Organization course. It demonstrates the fundamental architecture and execution of RISC-V instructions, including instruction fetch, decode, execute, memory access, and write-back stages — all completed in one clock cycle.

🔧 Features
Single-cycle datapath implementation
Support for RISC-V base integer instruction set (RV32I)
ALU design with arithmetic and logical operations
Instruction and data memory modules
Register file implementation
Control unit for generating control signals
Modular and scalable Verilog codebase

📁 Project Structure
alu.v – Arithmetic Logic Unit
control_unit.v – Generates control signals based on opcodes
datapath.v – Integrates all components into a single-cycle datapath
memory.v – Memory module for instruction and data
register_file.v – 32-register storage
riscv_top.v – Top-level module for simulation
testbench.v – Testbench for simulation using sample programs

🚀 How to Run
Simulate the design using Vivado, or any Verilog simulator. Testbench files are included for initial validation.
