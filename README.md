# 4-Bit Arithmetic Logic Unit (ALU)

This repository contains the design and implementation of a **4-bit Arithmetic Logic Unit (ALU)** built using **basic digital logic components and ICs**. The ALU performs arithmetic and logical operations on two 4-bit inputs and displays the result using a 7-segment display.

The project is designed and simulated using a digital logic simulation tool and is intended for learning and demonstration purposes in **Digital Electronics / Computer Architecture** courses.

---

## 🔧 Features

- 4-bit input operands **A (A3–A0)** and **B (B3–B0)**
- Supports multiple operations:
  - Addition
  - Subtraction
  - Bitwise AND
  - Bitwise OR
  - Bitwise XOR
- Operation selection using control/select lines
- Carry generation and propagation
- Output displayed using **7-segment displays**
- Implemented using standard **TTL ICs (74xx series)**

---

## 🧠 ALU Architecture Overview

The ALU is composed of:
- **Arithmetic unit** (adder/subtractor)
- **Logic unit** (AND, OR, XOR gates)
- **Multiplexers** to select the required operation
- **Decoder / display driver** for output visualization
- **Control logic** for operation selection

Each operation is performed in parallel, and the final result is selected using multiplexing logic.

---

## 🧩 Components Used

- Logic Gates (AND, OR, XOR, NOT)
- Full Adders
- Multiplexers
- ICs such as:
  - 74161 (Counters)
  - 74163
  - 74165
  - 7485 (Comparator)
- 7-segment display
- Clock and enable inputs
- Power supply (+5V, GND)

---

## 📷 Circuit Diagram

Below is the complete circuit diagram of the 4-bit ALU:

![4-bit ALU Circuit](./alu_circuit.png)

> *(Replace `alu_circuit.png` with the actual image filename if different.)*

---

## ⚙️ How It Works

1. Two 4-bit binary numbers are applied as inputs.
2. Select lines determine the operation to be performed.
3. Arithmetic or logical computation is carried out internally.
4. The result is routed to the output section.
5. Final output is displayed using 7-segment displays.

---

## 🚀 How to Run / Simulate

1. Open the circuit file in your digital logic simulator (e.g., Logisim / Multisim / Proteus).
2. Apply input values to A and B.
3. Set the select lines according to the desired operation.
4. Observe the output on the display.

---

## 📚 Applications

- Educational demonstration of ALU operation
- Understanding CPU datapath fundamentals
- Digital electronics laboratory experiments
- Computer architecture basics

---

## ✨ Future Improvements

- Extend to **8-bit ALU**
- Add status flags (Zero, Carry, Overflow)
- Integrate with a simple CPU design
- Optimize gate-level implementation

---

## 👤 Author

**Priyanshe Rout**  
Electronics / Digital Systems Enthusiast  

---

## 📜 License

This project is open-source and available for educational use.
