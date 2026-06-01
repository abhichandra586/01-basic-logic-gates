# 01-Basic Logic Gates (Verilog Implementation)

This repository contains the Verilog HDL implementation, testbenches, and functional simulation waveforms for individual foundational digital logic gates: **AND**, **OR**, and **NOT**. This project serves as a baseline for my hardware description language (HDL) and VLSI design portfolio.

## 📁 Project Structure
The repository is organized according to standard digital design industry practices:
* **`src/`** - Hardware Description Language (HDL) source codes
* **`tb/`** - Testbenches providing input stimulus for functional verification
* **`sim/`** - Value Change Dump (`.vcd`) files and timing diagrams

---

## 📐 Logic Verification & Design Details

### 1. AND Gate
* **Files:** `src/and_gate.v`, `tb/and_gate_tb.v`, `sim/and_gate.vcd`
* **Boolean Expression:** $Y = A \cdot B$
* **Truth Table:**
  | Input A | Input B | Output Y |
  | :---: | :---: | :---: |
  | 0 | 0 | 0 |
  | 0 | 1 | 0 |
  | 1 | 0 | 0 |
  | 1 | 1 | 1 |

* **Waveform Evidence:**
  ![AND Gate Waveform](./sim/and_gate_waveform.png)

---

### 2. OR Gate
* **Files:** `src/or_gate.v`, `tb/or_gate_tb.v`, `sim/or_gate.vcd`
* **Boolean Expression:** $Y = A + B$
* **Truth Table:**
  | Input A | Input B | Output Y |
  | :---: | :---: | :---: |
  | 0 | 0 | 0 |
  | 0 | 1 | 1 |
  | 1 | 0 | 1 |
  | 1 | 1 | 1 |

* **Waveform Evidence:**
  ![OR Gate Waveform](./sim/or_gate_waveform.png)

---

### 3. NOT Gate
* **Files:** `src/not_gate.v`, `tb/not_gate_tb.v`, `sim/not_gate.vcd`
* **Boolean Expression:** $Y = \bar{A}$
* **Truth Table:**
  | Input A | Output Y |
  | :---: | :---: |
  | 0 | 1 |
  | 1 | 0 |

* **Waveform Evidence:**
  ![NOT Gate Waveform](./sim/not_gate_waveform.png)

---

## 🛠️ Simulation & Verification Tools
* **Simulator:** Icarus Verilog (`iverilog`)
* **Waveform Viewer:** GTKWave

---
*Developed as part of my VLSI and Digital Electronics learning portfolio.*
