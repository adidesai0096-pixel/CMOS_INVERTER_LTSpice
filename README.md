# CMOS Inverter Design and Simulation Using LTspice

## 1. Project Overview
This project focuses on the design and simulation of a CMOS inverter using LTspice. A CMOS inverter is a fundamental digital logic circuit that performs the NOT operation. It uses complementary PMOS and NMOS transistors to produce an output opposite to the input.

## 2. Objectives
- To understand the basic working principle of a CMOS inverter.
- To design a transistor-level CMOS inverter circuit.
- To simulate the circuit using LTspice.
- To observe and analyze the input and output waveforms.
- To verify the NOT gate truth table.

## 3. Software Used
- **LTspice** – Circuit design and simulation.
- **GitHub** – Project file storage and documentation.

## 4. Components Used
- One PMOS transistor
- One NMOS transistor
- 5 V DC supply
- Pulsed input voltage source
- Ground reference
- Transient analysis directive

## 5. Circuit Description
The CMOS inverter consists of a PMOS transistor connected between the positive supply and the output, and an NMOS transistor connected between the output and ground. Both transistor gates are connected to the input.

When the input is LOW, the PMOS transistor turns ON and the NMOS transistor turns OFF, making the output HIGH. When the input is HIGH, the PMOS transistor turns OFF and the NMOS transistor turns ON, making the output LOW.

## 6. Truth Table

| Input (VIN) | Output (VOUT) |
|---|---|
| 0 (LOW) | 1 (HIGH) |
| 1 (HIGH) | 0 (LOW) |

## 7. Simulation
Transient analysis is used to observe the input and output voltage waveforms over time. The expected output waveform is the logical inverse of the input waveform.

**Simulation supply:** 5 V  
**Input signal:** Pulsed voltage from 0 V to 5 V

## 8. Results
The simulation is used to verify the operation of the CMOS inverter. The output should be HIGH when the input is LOW and LOW when the input is HIGH. The actual schematic and waveform screenshots are included in the repository for reference.

## 9. Applications
- Digital logic circuits
- Basic CMOS logic design
- Integrated circuit design
- Signal inversion
- Building blocks for more complex logic gates

## 10. Project Files
This repository contains:
- LTspice schematic file (`.asc`)
- Input and output waveform screenshot
- Project report (`.pdf`)
- Additional documentation, if applicable

## 11. Conclusion
This project demonstrates the fundamental operation of a CMOS inverter using LTspice. It provides practical experience in transistor-level circuit design, transient simulation, and verification of digital logic behavior.

## 12. Author
**Aditya Ramakant Desai**  
**Course:** VLSI Design  
**Training Provider:** Glow Logics  
**Department:** Electronics and Computer Engineering

---

*This project was completed for educational purposes as part of VLSI design training.*
