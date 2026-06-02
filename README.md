# Computational Physics: ODE Solvers in Python

This repository contains a computational physics notebook focused on the numerical solution of ordinary differential equations (ODEs) using Python.

The project implements classical numerical methods from scratch and compares them with `scipy.integrate.solve_ivp`.

## Notebook

- [`notebooks/computational_physics_ode_solvers.ipynb`](notebooks/computational_physics_ode_solvers.ipynb)

## Topics Covered

- Euler method
- Modified Euler method
- Milne-Simpson predictor-corrector method
- Carbon-14 radioactive decay
- Comparison with SciPy `solve_ivp`
- Simple harmonic motion as a second-order ODE
- Error analysis using exact analytical solutions

## Project Summary

The first part of the notebook estimates the age of an object using a Carbon-14 radioactive decay model. The problem is solved numerically using Euler, modified Euler and Milne-Simpson methods, and the results are compared with the exact analytical solution and SciPy's ODE solver.

The second part applies the modified Euler method to a physical second-order ODE: the simple harmonic oscillator. The numerical solution is compared with both the exact solution and SciPy's solver, and the accumulated numerical error is visualised.

## Technologies Used

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## How to Run

Install the dependencies:

```bash
pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook notebooks/computational_physics_ode_solvers.ipynb
```

The notebook does not require any external dataset.

## Kaggle Notes

This notebook can also be uploaded directly to Kaggle as an educational computational physics notebook. No Kaggle dataset input is required.

## Author

Alberto Reyes Castro  
London-based Physics graduate and MSc student in Artificial Intelligence Technology.
