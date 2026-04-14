# IQAP Project: Implementing Shor's Algorithm & QPE

**Author:** Malek BENAMROUCHE

## Overview

This project implements **Quantum Phase Estimation (QPE)** and the core period-finding subroutine of **Shor's algorithm** (`x ↦ aˣ mod N`) using Qiskit.  
It follows the two lab sessions:
- **Part 1 (TP_QPE)** – QPE implementation and analysis
- **Part 2 (TP_Shor)** – Oracle for modular multiplication + full Shor circuit

The accompanying **PDF report** contains all answers, circuit screenshots, plots, runtime analysis, and discussion.

## Files

- `TP_QPE - BENAMROUCHE Malek.ipynb` → Part 1: QPE (3-, 4-, 5-qubit examples, 1/3 approximation, etc.)
- `TP_Shor - BENAMROUCHE Malek.ipynb` → Part 2: Shor's oracle + QPE integration (with 7 mod 30 and other examples)
- `Rapport IQAP - BENAMROUCHE Malek.pdf` → Complete lab report (3 pages)

## Requirements

```bash
pip install qiskit qiskit-aer matplotlib numpy scipy
