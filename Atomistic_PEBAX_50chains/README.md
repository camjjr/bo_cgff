# Atomistic Model

# LAMMPS Simulation: Atomistic Pebax

This repository contains input files to perform molecular dynamics (MD) simulations using **LAMMPS**.  

---

## 📁 File Overview

| File | Description |
|------|--------------|
| `input.dat` | Main LAMMPS input script. Defines the simulation workflow, including initialization, potential setup, equilibration, and production runs. |
| `structure.dat` | Atomic structure file containing atom types, coordinates, and box dimensions. Used as the starting configuration. |
| `parameters.dat` | Potential parameter file. Defines pair coefficients, bond/angle parameters, or tabulated potentials used in the simulation. |

---


## ▶️ How to Run

```bash
lmp -in "input.dat"

