<div align="center">

# 🔌 DLD Circuits — Digital Logic Design Circuit Collection

![Digital Logic Design](https://img.shields.io/badge/Course-Digital%20Logic%20Design-blue?style=for-the-badge)
![Circuits](https://img.shields.io/badge/Circuits-25-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**A curated, categorized collection of Digital Logic Design (DLD) circuits — from basic gates to hierarchical decoders, multiplexers, and arithmetic units.**

</div>

---

## 📖 Overview

This repository is a complete visual reference of **25 hand-built digital logic circuits**, designed and simulated as part of a Digital Logic Design course. Every circuit is organized by category, making it easy to browse, study, or reference for coursework, interviews, or revision.

Whether you're learning combinational logic from scratch or brushing up before an exam, this repo walks through the building blocks of digital systems — one circuit at a time.

---

## 🗂️ What's Inside

| Category | Circuits | Description |
|---|---|---|
| 🔧 **Basic Gates & Latches** | 2 | Foundational gate-level logic and memory elements |
| ➕ **Adders & Arithmetic** | 7 | Binary/BCD addition, subtraction, and arithmetic units |
| 🔀 **Multiplexers** | 8 | Data selection circuits, built from scratch and combined |
| 🔁 **Demultiplexers** | 1 | Single-input, multi-output routing circuit |
| 🧩 **Decoders** | 5 | Hierarchical decoder designs (2x4 → 3x8 → 4x16 → 5x32) |
| 🔢 **Number Detectors** | 2 | Combinational logic for pattern/property detection |

**Total: 25 circuits**

---

## 📁 Repository Structure

```
DLD_Circuits/
├── 01_Basic_Gates_and_Latches/
│   ├── Making NOT from XOR.png
│   └── SR Latch.png
│
├── 02_Adders_and_Arithmetic/
│   ├── Half Adder.png
│   ├── 4-Bit Adder (A+B).png
│   ├── 8-Bit Adder (A+B).png
│   ├── 4-Bit 2's Complement.png
│   ├── 2 in 1 (Add+Subtract).png
│   ├── BCD Adder.png
│   └── Square of 3 Bit Numbers.png
│
├── 03_Multiplexers/
│   ├── 2x1 Multiplexer.png
│   ├── 2x1 Multiplexer (From Scratch).png
│   ├── 4x1 Multiplexer (From Scratch).png
│   ├── 2-to-1 Quadruple Multiplexer.png
│   ├── 17x1 MUX using 4x1 and 2x1 MUX(s).png
│   ├── Implementing Σm(1,3,4,11,12,13,14,15) Using 4x1 Multiplexer.png
│   ├── Implementing Σm(1,3,4,11,12,13,14,15) using Multiplexer.png
│   └── Using Multiplexer Implementing Σm(1,2,6,7).png
│
├── 04_Demultiplexers/
│   └── Demultiplexer.png
│
├── 05_Decoders/
│   ├── Decoder 3x8 (Hierarchical 2x4).png
│   ├── Decoder 4x16 (Hierarchical 2x4).png
│   ├── Decoder 4x16 (Hierarchical 3x8).png
│   ├── Decoder 5x32 (Hierarchical 3x8).png
│   └── Decoder with Enable Input.png
│
├── 06_Number_Detectors/
│   ├── EVEN, ODD & PRIME Detector.png
│   └── ODD Number Detector.png
│
├── README.md
└── LICENSE
```

---

## 🔍 Circuit Highlights

### 🔧 Basic Gates & Latches
- **Making NOT from XOR** — Deriving a NOT gate using only an XOR gate, tying one input high.
- **SR Latch** — The fundamental sequential storage element built from cross-coupled gates.

### ➕ Adders & Arithmetic
- **Half Adder** — The simplest 1-bit adder (Sum & Carry).
- **4-Bit / 8-Bit Adder (A+B)** — Ripple-carry adders scaled across multiple bits.
- **4-Bit 2's Complement** — Circuit for computing the two's complement of a 4-bit number.
- **2 in 1 (Add + Subtract)** — A single circuit that performs both addition and subtraction using XOR-controlled carry-in.
- **BCD Adder** — Binary-Coded Decimal adder with correction logic.
- **Square of 3-Bit Numbers** — Combinational logic to compute the square of a 3-bit input.

### 🔀 Multiplexers
- **2x1 / 4x1 Multiplexer (From Scratch)** — Built at gate level, no built-in MUX components.
- **2-to-1 Quadruple Multiplexer** — Four parallel 2x1 MUX channels.
- **17x1 MUX using 4x1 and 2x1 MUX(s)** — A large-scale multiplexer built hierarchically from smaller ones.
- **Implementing Σm(1,3,4,11,12,13,14,15) using MUX** — Boolean function implementation via multiplexer (two variations).
- **Using Multiplexer Implementing Σm(1,2,6,7)** — Another function realization using MUX-based logic.

### 🔁 Demultiplexers
- **Demultiplexer** — Single input routed to one of several outputs based on select lines.

### 🧩 Decoders
- **Decoder 3x8 (Hierarchical 2x4)** — 3-to-8 decoder built from smaller 2x4 decoders.
- **Decoder 4x16 (Hierarchical 2x4 / 3x8)** — Two different hierarchical approaches to build a 4x16 decoder.
- **Decoder 5x32 (Hierarchical 3x8)** — Large-scale decoder built from 3x8 decoder blocks.
- **Decoder with Enable Input** — Decoder design incorporating an enable control line.

### 🔢 Number Detectors
- **EVEN, ODD & PRIME Detector** — Combinational circuit that identifies number properties.
- **ODD Number Detector** — Dedicated logic to detect odd numbers.

---
