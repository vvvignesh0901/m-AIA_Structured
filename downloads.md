---
title: Downloads
nav_order: 99
---

# Downloads

Script versions of the [Post-processing](post-processing.html) notebooks. They contain only the code, without the theory and schematics, and reproduce the results shown on the website when run.

| Notebook | Description | Requirements |
|---|---|---|
| <a href="notebooks/wall_surface_coefficients.ipynb" download>wall_surface_coefficients.ipynb</a> | Surface Cp and Cf from XFOIL, integrated lift and drag, summary plot. | Python 3 with NumPy, Matplotlib and Jupyter; XFOIL |

## Using the notebooks

1. Download the notebook and open it in Jupyter.
2. In the parameters cell, set `XFOIL_BIN` to the path of your XFOIL binary.
3. Run all cells.

The notebooks run XFOIL with its graphics disabled. If your XFOIL build was compiled with floating-point traps (for example `-ffpe-trap=invalid,zero` in the XFOIL Makefile), it can crash in that mode. In that case, rebuild XFOIL without those flags.
