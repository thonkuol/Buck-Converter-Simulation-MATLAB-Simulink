# Buck Converter Simulation using MATLAB/Simulink

## Overview

This project presents the design and simulation of a DC-DC Buck Converter using MATLAB/Simulink.

The converter is designed to reduce a 24 V DC input into approximately 12 V DC while operating in Continuous Conduction Mode (CCM). The simulation results are compared with theoretical calculations to evaluate converter performance and efficiency.

---

## Objectives

- Understand Buck Converter operation
- Design the converter in MATLAB/Simulink
- Analyze voltage and current waveforms
- Verify Continuous Conduction Mode (CCM)
- Compare theoretical and simulated results

---

## Software Used

- MATLAB
- Simulink
- Simscape Electrical

---

## Circuit Parameters

| Parameter | Value |
|------------|--------|
| Input Voltage | 24 V |
| Output Voltage | 12 V (Theoretical) |
| Switching Frequency | 20 kHz |
| Duty Cycle | 50% |
| Inductor | 1 mH |
| Capacitor | 220 µF |
| Load Resistance | 10 Ω |

---

## Design Equations

Output Voltage

Vout = D × Vin

Output Current

Iout = Vout / R

Output Power

Pout = Vout × Iout

---

## MATLAB/Simulink Model

Insert the Simulink model screenshot below.

![Simulink Model](Images/Simulink_Model.png)

---

## Output Voltage

![Voltage](Images/Output_Voltage.png)

---

## Output Current

![Current](Images/Output_Current.png)

---

## Results

| Parameter | Theoretical | Simulation |
|------------|------------:|-----------:|
| Output Voltage | 12 V | 11.54 V |
| Output Current | 1.20 A | 1.154 A |
| Efficiency | 100% | 92.4% |

---

## Discussion

The simulation closely matches the theoretical calculations.

The small deviation is mainly caused by:

- MOSFET conduction losses
- Diode forward voltage drop
- Switching losses

The converter successfully operates in Continuous Conduction Mode.

---

## Applications

- Electric Vehicles
- Battery Chargers
- Solar Energy Systems
- Embedded Systems
- Industrial Control
- DC Motor Drives

---

## Files Included

- MATLAB Simulink Model (.slx)
- Project Report (.pdf)
- Simulation Images
- README

---

## Author

Thon Kuol

Electrical Engineering (Control Systems) Student

Data Analyst
