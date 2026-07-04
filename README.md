# UDCF Instrumented Pendulum Rig v2.1
**Unified Dimensionless Cutting Framework | Digital Twin Analysis**

## Overview
This repository contains the source code for the UDCF Instrumented Pendulum Rig v2.1. This simulator serves as a **Digital Twin**, allowing researchers to predict severance success ($\eta \geq 1$) or sub-critical impact based on the kinematic energy of a swinging pendulum.

## Key Features
- **Dynamic Unit Conversion:** Input data in $m, mm, \mu m, MPa, Pa, mm^2,$ or $m^2$.
- **Real-time Physics Engine:** Calculates Velocity ($v$) and Kinetic Energy ($E_k$) instantly.
- **Dimensionless Analysis:** Determines the Efficiency Index ($\eta$) using the governing UDCF equation.
- **Visual Schematic:** Interactive SVG-based rig that animates the impact and material failure.

## The Governing Equation
The rig operates on the principle:
$$\eta = k_{\gamma} \left( \frac{mv^2}{2d\tau_{ult}A} \right) \geq 1$$

Where:
- $k_{\gamma}$ = Recovery Factor
- $m$ = Tool Mass
- $v$ = Impact Velocity
- $d$ = Specimen Thickness
- $\tau_{ult}$ = Ultimate Shear Strength
- $A$ = Contact Area

## Installation & Usage
1. Clone the repository.
2. Install dependencies: `npm install`
3. Run the application: `npm start`
4. Adjust the "Rig Configuration" and "Specimen Properties" to observe real-time changes in $\eta$.

## Research Body
**Lead Researcher:** Clifford Yeboah  
**Institute:** The Yeboah Institute Research

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Citation
If you use this Digital Twin in your research, please cite it as:
> Yeboah, C. (2026). UDCF Instrumented Pendulum Rig v2.1 [Software]. The Yeboah Institute Research.
