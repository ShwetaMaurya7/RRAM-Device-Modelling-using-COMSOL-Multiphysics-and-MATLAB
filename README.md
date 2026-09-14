# RRAM Device Modelling Using COMSOL Multiphysics and MATLAB LiveLink

This repository contains the work completed during my **SN Bose Internship Program 2026** at the **National Institute of Technology Silchar**.

## About the Internship

The internship focused on the **numerical modelling of filamentary Resistive Random-Access Memory (RRAM)** using **COMSOL Multiphysics 6.0** and **MATLAB LiveLink**.

The primary objective was to develop, automate, and debug a coupled multiphysics simulation framework for studying RRAM switching behaviour.

## Project Overview

RRAM switching is associated with the formation and rupture of a conductive filament, resulting in transitions between the **High Resistance State (HRS)** and **Low Resistance State (LRS)**.

The project involved modelling the electro-thermal behaviour of the device and studying filament evolution using a thermodynamic/free-energy framework.

## Work Performed

- Developed a **2D axisymmetric RRAM device model** in COMSOL Multiphysics.
- Modelled a metal–insulator–metal structure containing TiN electrodes and HfO₂-based regions.
- Implemented coupled **Heat Transfer, Electric Currents, Electrical Circuit, and electromagnetic heating** physics.
- Studied a thermodynamic/free-energy framework for modelling filament evolution.
- Integrated COMSOL with MATLAB using **LiveLink for MATLAB**.
- Automated the **OFF → SET → ON → RESET** simulation workflow.
- Performed systematic debugging of MATLAB and COMSOL models.
- Extracted simulation data including voltage, current, temperature, filament/gap parameters, and free-energy terms.
- Developed MATLAB-based post-processing for **I–V characterization**.
- Investigated numerical issues affecting RESET convergence and device-voltage scaling.

## Software & Tools

- COMSOL Multiphysics 6.0
- MATLAB
- MATLAB LiveLink for COMSOL

## Key Outcomes

The internship resulted in a functional **COMSOL–MATLAB simulation and post-processing framework**.

The four simulation stages—**RRAM_OFF, RRAM_SET, RRAM_ON, and RRAM_RESET**—were organized into an automated workflow capable of building models, running simulations, extracting data, performing free-energy minimization, and aggregating results.

A significant part of the work involved **systematic debugging and model repair**, including issues related to MATLAB syntax, COMSOL parameters, domain selections, mesh settings, parameter naming, and server/memory management.

## Current Status & Limitations

The developed simulation pipeline was successfully made executable and capable of generating stage-wise numerical data.

However, the results are considered **preliminary numerical outputs rather than fully validated RRAM switching characteristics**.

The following aspects require further investigation:

- RESET free-energy minimization and convergence
- Device-voltage scaling
- Quantitative validation against reference I–V characteristics
- Ramp-rate and cycle-to-cycle studies
- Quantitative comparison of SET/RESET behaviour with literature

## Repository Contents

| File | Description |
|---|---|
| `SN_Bose_Internship_Report.pdf` | Detailed internship report |
| `RRAM_Internship_Presentation_Sweta_Maurya_FINAL.pptx` | Final internship presentation |

## Internship Details

**Program:** SN Bose Internship Program, 2026  
**Institution:** National Institute of Technology Silchar  
**Department:** Electronics and Instrumentation Engineering  
**Intern:** Sweta Maurya  
**Duration:** June–July 2026  
**Supervisor:** Dr. Shivendra Kumar Pandey

## References

The modelling framework and background study were informed by relevant RRAM literature, including the thermodynamic modelling work by **D. Niroula and V. G. Karpov**, along with COMSOL Multiphysics and MATLAB LiveLink documentation.
