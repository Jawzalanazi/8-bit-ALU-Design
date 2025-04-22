### 🧮 8-bit ALU Design in Logisim

This project implements a simple 8-bit Arithmetic Logic Unit (ALU) using **Logisim**. The ALU performs arithmetic and logical operations on two 8-bit inputs. It includes custom-built circuits for a **1-bit Full Adder**, **1-bit ALU**, and a final **8-bit ALU** by chaining eight 1-bit ALUs. Additional shift operations are also implemented.

#### ✅ Features:
- **1-bit Full Adder**: Built from basic gates (not Logisim's built-in).
- **1-bit ALU**: Supports AND, OR, XOR, XNOR, ADD/SUB based on 3-bit op-code.
- **8-bit ALU**: Processes 8-bit numbers using splitters and chained 1-bit ALUs.
- **Shift Operations**: Includes logical shift right (SHR) and left (SHL).
- **Custom Multiplexer**: Used for operation selection.
- **Carry-in/Carry-out**: Managed across all bits for addition and subtraction.

#### 💡 Tools & Concepts:
- **Logisim Circuits** (`FA-1Bit`, `ALU-1bit`, `ALU`)
- **Data Structures**: Multiplexers, splitters, and custom components
- **Binary Arithmetic & Logic**
- **Bitwise Operations & Shifting**

This project was completed as part of **CS 125** course requirements and includes a report and circuit screenshots.
