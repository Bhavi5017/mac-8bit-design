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

![MAC](mac_schematic.png)

---

## 🔧 Submodules

### Multiplier

![Multiplier](multiplier.png)

### Adder

![Adder](adder_8bit.png)

### Register

![Register](register_8bit.png)

### Multiplexer

![MUX](mux_41.png)

---

## 🧪 Testbench

![Testbench](mac_testbench.png)

---

## 📊 Results

### Waveform 1

![Waveform1](waveform1.png)

### Waveform 2

![Waveform2](waveform2.png)

---

## 🧷 Symbol

![Symbol](mac_symbol.png)

---

## 🛠 Tools Used

* Cadence Virtuoso
* Spectre Simulator

---

## 👩‍💻 Author

Bhavitha N
