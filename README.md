Sure! Here's a `README.md` file for your Chua's Circuit simulation project:

---


 🌀 Chua's Circuit Simulation in Python

This project simulates **Chua’s Circuit**, a classic example of a simple electronic circuit that exhibits **chaotic behavior**. The simulation is implemented in Python using `scipy` for solving the differential equations and `matplotlib` for visualization.

---

 📚 Overview

**Chua’s Circuit** is governed by a system of three non-linear differential equations involving a piecewise-linear function that models the Chua diode. It’s widely used in the study of nonlinear dynamics and chaos theory.

 System of Equations:

```
dx/dt = α (y - x - h(x))  
dy/dt = x - y + z  
dz/dt = -β y

Where h(x) = m₁x + 0.5(m₀ - m₁)(|x + 1| - |x - 1|)
```

---



Make sure you have the following Python packages installed:

```bash
pip install numpy scipy matplotlib
```

---

## 🚀 How to Run

1. Open the `chua_simulation.ipynb` file in JupyterLab or Jupyter Notebook.
2. Run all the cells to simulate the circuit and visualize the attractor and time series.

---

## 📈 Output

- A **3D plot** showing the Chua attractor.
- A **time-series plot** of x(t), y(t), z(t).

---

## ⚙️ Parameters Used

| Parameter | Value   | Description               |
|----------:|--------:|---------------------------|
| α         | 15.6    | Controls nonlinearity     |
| β         | 28.0    | Influences damping        |
| m₀        | -1.143  | Slope of inner region     |
| m₁        | -0.714  | Slope of outer region     |
| Initial State | [0.7, 0.0, 0.0] | Starting point in phase space |

---

## 📎 References

- [Chua's Circuit - Wikipedia](https://en.wikipedia.org/wiki/Chua%27s_circuit)
- M. P. Kennedy, "Three Steps to Chaos. II. A Chua’s Circuit Primer", IEEE Transactions on Circuits and Systems, 1993.

---

## 🧠 Author

Made with 💡 by Paramveer singh

---

## 📂 License

This project is open source and free to use for educational and research purposes.
```

