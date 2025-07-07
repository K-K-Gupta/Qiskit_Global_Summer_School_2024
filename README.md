# Qiskit Global Summer School 2024 – Lab Solutions

This repository contains my solutions to the Jupyter notebooks from the **Qiskit Global Summer School (QGSS) 2024**.

The QGSS is a two-week intensive program designed to equip aspiring quantum researchers and industry professionals with the skills needed to navigate the evolving landscape of quantum computing. The 2024 edition—the fifth annual installment—focused on preparing participants for the era of **quantum utility** through a hands-on, application-driven approach. The program comprised four labs, each targeting key areas of near-term quantum computing.

---

## 🧪 Lab Summaries

### 🔧 Lab 1: Circuit Transpilation
This lab introduced the fundamentals of **quantum circuit transpilation**. We began by analyzing circuit characteristics that influence execution on quantum hardware, then applied Qiskit’s default transpiler. Finally, we built custom transpilation processes tailored for hardware optimization.

### 📊 Lab 2: Error Metrics – EPLG & LF
We explored how to calculate **Error Per Layered Gate (EPLG)** and **Layer Fidelity (LF)**—two important metrics that help quantify circuit-level errors. These measurements are essential for estimating the overhead involved in applying error mitigation techniques to utility-scale workloads.

### 🛡️ Lab 3: Error Suppression and Mitigation
This lab focused on using the **Estimator primitive** from Qiskit Runtime to explore various **error mitigation strategies**, including:

- Dynamical Decoupling  
- Measurement Error Mitigation  
- Gate Twirling  
- Zero Noise Extrapolation (ZNE)

Different combinations of these techniques were applied to assess their effectiveness in improving result accuracy.

### 🔬 Lab 4: Simulating Spin Chains at Utility Scale
In the final lab, we simulated the dynamics of a **Heisenberg spin chain** in a transverse magnetic field using the **Qiskit Patterns** framework. The simulation was built to be utility-scale and incorporated multiple optimization and error mitigation methods to improve output fidelity.

> **Note:** The labs were designed for execution on the **IBM Brisbane** quantum system (127 qubits). Due to time constraints, I was unable to run experiments on real quantum hardware and used simulations instead.

---

## 📁 Repository Structure

