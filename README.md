# Verilog HDL Lab - NIELIT Calicut

A collection of beginner-friendly Verilog HDL exercises prepared for the "VLSI for Beginners" course at **National Institute of Electronics and Information Technology, Calicut**.

---

## 🧪 Lab Exercises

1. **Basic Logic Gates** (OR, AND, NOT, NAND, XOR, NOR)
2. **Half Adder** (Dataflow / Behavioral / Structural)
3. **Full Adder** (Dataflow / Behavioral / Structural)
4. **Half Subtractor** (Dataflow / Behavioral / Structural)
5. **Full Subtractor** (Dataflow / Behavioral / Structural)
6. **4:1 Multiplexer**
7. **4-bit Synchronous Up Counter**

---

## 📦 Tools Used
- Verilog HDL
- Icarus Verilog / Xilinx Vivado / ModelSim
- GTKWave

---

## 📸 Waveforms
Waveform files (`.vcd`) or screenshots are stored in the `waveforms/` directory.

---

## 💡 How to Run (Icarus Verilog)

```bash
iverilog -o sim out.v
vvp sim
gtkwave dump.vcd
