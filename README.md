8-Bit ALU Design Using Verilog HDL

Project Overview

This project focuses on designing and simulating an 8-Bit Arithmetic Logic Unit (ALU) using Verilog Hardware Description Language (HDL).

An ALU is an important component of the Central Processing Unit (CPU). It performs arithmetic and logical operations on binary data. This project demonstrates how multiple operations can be implemented in a single digital circuit using Verilog HDL.

Objectives

- To design an 8-Bit Arithmetic Logic Unit using Verilog HDL.
- To perform arithmetic and logical operations.
- To understand opcode-based operation selection.
- To verify the design using a Verilog testbench.
- To understand the practical applications of ALU in digital systems.

Operations Performed

The designed ALU supports the following operations:

Opcode| Operation| Description
000| Addition| Adds A and B
001| Subtraction| Subtracts B from A
010| AND| Performs bitwise AND
011| OR| Performs bitwise OR
100| XOR| Performs bitwise XOR
101| NOT| Inverts the bits of A

Tools and Technologies Used

- Hardware Description Language: Verilog HDL
- Simulation Platform: EDA Playground
- Verification: Verilog Testbench

Working Principle

The ALU accepts two 8-bit binary inputs (A and B) and a control signal (opcode). Based on the selected opcode, the ALU performs the corresponding arithmetic or logical operation and generates the output.

A testbench is used to provide different input combinations and verify the correctness of the output through simulation.

Project Files

The repository contains the following files:

- "alu.v" – Verilog code for the 8-Bit ALU.
- "alu_tb.v" – Testbench code for verifying ALU operations.
- "simulation_waveform.png" – Simulation waveform showing the output of different operations.

Note: Include only the files that you have actually uploaded to the repository.

Simulation Results

The ALU design is tested using different input combinations and opcode values. The simulation waveform verifies the correct execution of all implemented arithmetic and logical operations.

Applications

- Microprocessors and microcontrollers.
- Central Processing Units (CPU).
- Embedded systems.
- Digital computing systems.
- Digital signal processing.

Conclusion

The 8-Bit ALU was successfully designed using Verilog HDL and verified through simulation. The project helped in understanding arithmetic and logical operations, opcode selection, and digital circuit verification.

Author

Hemanth B

Electronics and Communication Engineering (ECE)

License

This project is created for educational purposes.
