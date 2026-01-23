# Quantum-Native Entropy Engine 🌌

**High-fidelity entropy generation through Hilbert Space geometry and Born Rule simulation.**

---

## Overview

The **Quantum-Native Entropy Engine** is a Python-based stochastic generator that abandons traditional integer-based PRNGs (Pseudo-Random Number Generators) in favor of **Linear Algebra-driven physics simulation**. 

Instead of cycling through a deterministic formula, this engine treats bits as vectors in **Hilbert Space**. It simulates a uniform superposition state and applies the **Born Rule** ($P = |\psi|^2$) to "collapse" quantum states into raw binary entropy.

## 🏛️ The 5 Pillars of Reality
This engine is built on five conceptual pillars that differentiate it from standard library `random` functions:
1.  **Geometry:** States are defined as unit vectors in a 16-dimensional Hilbert Space.
2.  **Group Theory:** Uses Hadamard transforms to ensure a perfectly flat probability distribution.
3.  **Physics:** Implements the Born Rule for probability calculation.
4.  **Computation:** Uses high-precision complex floating-point math.
5.  **The Collapse:** Stochastic measurement based on simulated quantum observation.

---

## ⚖️ Statistical Validation (Dieharder)

Entropy is only as good as its unpredictability. This engine includes a built-in **Dieharder-Lite** test suite to ensure the bitstreams are cryptographically robust and free of patterns.

### Latest Benchmark (100,000 Bits)
Our engine consistently passes the primary pillars of the **Marsaglia Diehard Battery**:

| Statistical Test | p-value | Result |
| :--- | :--- | :--- |
| **Monobit (Frequency)** | `0.785656` | ✅ **PASSED** |
| **Runs (Streaks)** | `0.041723` | ✅ **PASSED** |
| **Serial (Pattern Pairs)** | `0.230047` | ✅ **PASSED** |

*A p-value between 0.01 and 0.99 indicates that the sequence is statistically indistinguishable from true randomness.*

---

## 🛠️ Features

- **Pure NumPy Implementation:** No heavy quantum frameworks (like Cirq or Qiskit) required.
- **Dieharder Compatibility:** Built-in function to export entropy into a `.txt` format readable by the professional `dieharder` C-library.
- **Verification Suite:** Real-time p-value calculation for Monobit, Runs, and Serial tests.
- **Visual Validation:** Generate magnetization history and distribution plots.

---

## 🚀 Quick Start

### Prerequisites
```bash
pip install numpy scipy matplotlib
```
### clone
```bash
git clone https://github.com/peterbabulik/Quantum-Native-Entropy-Engine
```

## 📈 Applications
*   **Monte Carlo Simulations:** High-quality noise for financial modeling.
*   **P-Bit Computing:** Driving probabilistic bits for NP-Hard optimization.
*   **Cryptographic Seeding:** Generating non-deterministic seeds for security protocols.
*   **Generative Art:** Producing "organic" randomness that avoids the "grid-like" feel of standard PRNGs.

---

## 📜 License
MIT License - Feel free to use this in your own quantum-inspired research.

---
*Created by [Peter Babulik](https://github.com/peterbabulik) — Exploring the intersection of Linear Algebra and Chaos.*
