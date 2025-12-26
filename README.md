# Physics-Simulation-Year-1
"Modeling Simple and Damped Harmonic Motion using Semi-implicit Euler integration. Features real-time energy tracking and phase space visualization

## Project Overview
This Jupyter Notebook performs a comparative analysis of Simple Harmonic Motion (SHM). It is divided into two sections to demonstrate the transition from theoretical physics to realistic modeling.

## Part 1: The Ideal System
We first simulate a frictionless pendulum to validate the numerical stability of the **Euler-Cromer method**.
* **Result:** The simulation produces a stable sine wave with constant amplitude, confirming that the integration method conserves energy over time.

## Part 2: The Realistic System (Damped)
We then introduce a damping term ($-\gamma\omega$) to simulate air resistance.
* **Physics:** The differential equation becomes $\alpha = -(g/L)\sin(\theta) - \gamma\omega$.
* **Phase Space Analysis:** We plot Angular Velocity vs. Angle. The resulting **spiral trajectory** visually demonstrates the system losing energy and settling into the equilibrium attractor at $(0,0)$.

## Technologies
* **Python** (NumPy, Matplotlib)
* **Numerical Methods:** Semi-implicit Euler (Euler-Cromer)

## How to View
Click the `.ipynb` file above to see the code, the equations, and the generated graphs.
