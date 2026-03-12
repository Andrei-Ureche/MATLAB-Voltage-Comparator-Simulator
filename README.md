# MATLAB Voltage Comparator Simulator

## Overview
An interactive GUI-based simulation tool developed in MATLAB to analyze Op-Amp comparator behavior and transfer functions. The application provides real-time visualization of the practical impacts of hysteresis and output saturation in electronic design for both inverting and non-inverting configurations.

## System Architecture
* **GUI Engine:** Built using MATLAB App Designer, featuring a responsive interface with dynamic sliders for $V_{ref}$, $V_{sat}$, and resistor values ($R_1, R_2$).
* **Mathematical Modeling:** Implements rigorous logic for both Inverting and Non-Inverting Schmitt Trigger configurations to simulate real-world circuit response.
* **Hysteresis Analysis:** Features a dedicated module to demonstrate noise immunity and threshold switching loops ($V_{T1}, V_{T2}$).

## Performance Summary
| Metric | Functionality | Result |
| :--- | :--- | :--- |
| **Simulation Modes** | Inverting / Non-Inverting | Real-time Toggle |
| **Visualizations** | Hysteresis & Transfer Curves | High-Accuracy $V_{out}$ vs $V_{in}$ Plots |
| **User Interface** | Parameter-Driven GUI | Interactive Control |
