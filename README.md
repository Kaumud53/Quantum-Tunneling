# ⚛️ Quantum Tunneling Simulation and Visualization

This repository contains Python scripts that simulate and visualize **quantum tunneling**, a key quantum mechanical phenomenon where particles have a nonzero probability of penetrating energy barriers that classical particles cannot.

## 📁 Contents

### 1. `Quantum tunneling.py`
Simulates and plots the **transmission coefficient (T)** for a particle encountering a rectangular potential barrier:
- Varies **energy** or **barrier width**.
- Handles edge cases for `E < V₀`, `E = V₀`, and `E > V₀`.
- Produces two clear plots:
  - Transmission coefficient vs. energy
  - Transmission coefficient vs. barrier width

### 2. `Quantum tunneling animation.py`
Visualizes a **Gaussian wave packet** interacting with a potential barrier:
- Constructs a spatial grid and finite-difference Hamiltonian.
- Evolves the wavefunction using a spectral method (eigenvalue decomposition).
- Animates both the **real** and **imaginary** parts of the wavefunction.
- Exports an animated `.gif` of the quantum tunneling process.

## 📊 Example Outputs

### Wave Packet Animation
- Output: `wave.gif`  
  ![wave.gif](wave.gif)

## 🧠 Concepts Illustrated
- Quantum tunneling
- Time-dependent Schrödinger equation
- Wavefunction normalization and time evolution
- Finite difference methods
- Eigenvalue problems in quantum mechanics

## 🛠️ Dependencies

Make sure you have the following packages installed:

```bash
pip install numpy matplotlib ipython
