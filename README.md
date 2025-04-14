# Chua-s-circuit-simulation
# 🌀 Chua's Circuit Simulation in Python

This project simulates **Chua’s Circuit**, a classic example of a simple electronic circuit that exhibits **chaotic behavior**. The simulation is implemented in Python using `scipy` for solving the differential equations and `matplotlib` for visualization.

---

## 📚 Overview

**Chua’s Circuit** is governed by a system of three non-linear differential equations involving a piecewise-linear function that models the Chua diode. It’s widely used in the study of nonlinear dynamics and chaos theory.

### System of Equations:

dx/dt = α (y - x - h(x))
dy/dt = x - y + z
dz/dt = -β y

Where h(x) = m₁x + 0.5(m₀ - m₁)(|x + 1| - |x - 1|)
--

## 🛠 Requirements

Make sure you have the following Python packages installed:

```bash
pip install numpy scipy matplotlib

---

