# Wind Turbine Grid-Tied Simulation in PSCAD

This project models a complete Wind Energy Conversion System (WECS) connected to the electrical grid using PSCAD. It includes turbine modeling, generator dynamics, power converter control, and grid integration. The system is designed to simulate real-time power flow, transient behavior, and energy control strategies for renewable energy applications.

---

## Features

- Variable-speed wind turbine with pitch and torque control (MOD 2)
- Synchronous generator for mechanical-to-electrical energy conversion
- Full-scale AC–DC–AC converter with:
  - 6-pulse rectifier
  - DC link capacitor protection
  - α-angle controlled inverter
- Step-up Y–Y transformer for voltage scaling and galvanic isolation
- Grid connection through Point of Common Coupling (PCC)
- Real-time monitoring of:
  - Active/Reactive Power (P + jQ)
  - Mechanical speed (Wm) and torque (Tm)
  - DC link voltage (Vdc)
  - Grid voltages and waveform response

---

## Simulation Goals

- Analyze steady-state and dynamic system behavior
- Evaluate the control performance of the turbine and converter
- Study power injection and synchronization at the grid interface
- Understand the interaction of wind generation with the utility grid

---

## Files Included

- `WECS_Simulation.pscx` – Main PSCAD project file  
- `components/` – Custom control blocks (pitch controller, α-angle modulator)  
- `results/` – Graphs and waveform captures (P, Q, Vdc, etc.)  
- `README.md` – Project documentation

---

## Prerequisites

- **Software:** PSCAD v4.6+ or v5.x  
- **Basic knowledge of:**  
  - Power electronics  
  - Wind energy systems  
  - Grid synchronization and control strategies

---

## Author

**Raein Layegh Pour**  
Electrical Engineering @ TMU  
[LinkedIn](https://linkedin.com/in/raeinlp) • [Portfolio](https://raeinportfolio.com)

---

## License

This project is for educational and research use only. Not for commercial distribution.
