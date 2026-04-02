# Por-C60_complex (TD-)DFT Results
This repository contains the raw data of the (TD-)DFT calculations on the **ZnPD** monomer, the homodimers **ZnP-ZnP** and **C60-C60**, as well as the heterodimers **ZnP-HC60** and **ZnPH-C60**. The data are structured after method and property as shown below.

## Data in the Repository
---
### [geoms](geoms/) - Optimized Geometries
XYZ files of the optimized ground (GS) and transition states (TS) with coordinates given in Angström.

  - **Ground States** - computational details (Gaussian 16W)
    ```text
    CAM-B3LYP def2SVP OPT freq SCF=(Tight) Integral=(Grid=Superfinegrid) NoSymm SCRF(Solvent=Anisole) EmpiricalDispersion=GD3BJ

  - **Transition States** - computational details (Gaussian 16W)
    ```text
    CAM-B3LYP def2SVP OPT=(TS,CalcFC) freq SCF=(Tight) Integral=(Grid=Superfinegrid) NoSymm SCRF(Solvent=Anisole) EmpiricalDispersion=GD3BJ
---
