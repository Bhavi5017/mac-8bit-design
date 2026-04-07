# 🧠 8-bit MAC (Multiply-Accumulate) Design

## 📌 Overview

This project implements an 8-bit MAC (Multiply-Accumulate) unit using analog design in Cadence Virtuoso.

The MAC performs:

* Multiplication of inputs
* Accumulation using registers
* Controlled data flow using multiplexers

---

## 🧩 Components Used

* 8-bit Multiplier
* 8-bit Adder
* 8-bit Register (D Flip-Flops)
* 4:1 Multiplexers (8 units)

---

## 🖼️ MAC Schematic

![MAC](schematics/mac_schematic.png)

---

## 🔧 Submodules

### Multiplier

![Multiplier](schematics/multiplier.png)

### Adder

![Adder](schematics/adder.png)

### Register

![Register](schematics/register.png)

### Multiplexer

![MUX](schematics/mux.png)

---

## 🧪 Testbench

![Testbench](testbench/mac_testbench.png)

---

## 📊 Results

### Waveform 1

![Waveform1](results/waveform1.png)

### Waveform 2

![Waveform2](results/waveform2.png)

---

## 🧷 Symbol

![Symbol](symbol/mac_symbol.png)

---

## 🛠 Tools Used

* Cadence Virtuoso
* Spectre Simulator

---

## 👩‍💻 Author

Bhavitha N
