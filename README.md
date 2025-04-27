# Quantum Systems Simulation Results

## Overview

This repository contains Python code and results for numerical simulations of various quantum systems. The implementations are based on computational methods presented in the paper "Computations in Quantum Mechanics Made Easy" by Korsch and Rapedius, with a focus on optimization and translation from MATLAB to Python using libraries like NumPy and SciPy.

The project explores the following quantum mechanical systems and phenomena:

* **Bloch Oscillations:** Implementation of breathing and oscillatory modes, visualization of wavefunction evolution, and demonstration of quantum tunneling effects.
* **Field-Flip System:** Simulation of directed transport with field flipping, showing alternating field direction effects, and tracking wavefunction propagation.
* **Angular Momentum System:** Calculation of rigid body Hamiltonian eigenvalues, verification of commutation relations, and analysis of asymmetric top energy distribution.
* **Pullen-Edmonds System:** Analysis of a 2D quantum oscillator with coupling, including visualization of eigenstate wavefunctions and energy level calculations.
* **Bose-Hubbard Dimer:** Fixed particle number analysis using multiple calculation methods:
    * Penalty term approach
    * Projection to fixed particle subspace
    * Jordan-Schwinger representation
    Comparison of different methodologies.
* **Lindblad Master Equation:** Open quantum system dynamics, time evolution of particle numbers, and demonstration of dissipative effects.
* **Double Well Potential:** Analysis of tunneling dynamics, energy level structure, and wavefunction visualization in position space.

## Code Implementation

The core computational methods are implemented in Python. Key techniques include:

* Matrix representations of quantum operators using NumPy.
* Eigenvalue and eigenvector computations using `numpy.linalg.eig()` and `scipy.linalg.eigh()`.
* Time evolution simulations using matrix exponentiation (`scipy.linalg.expm()`).
* Modeling open quantum systems with Lindblad master equations.
* Analysis of many-particle systems using the Bose-Hubbard model.

## Project Structure

* `project2.ipynb`: A Jupyter Notebook containing the Python code for the simulations and analysis.
* `Project proposal.pdf`: The initial project proposal outlining the objectives and methodology.
* `project2.pdf`: A presentation summarizing the computational methods and results.

## Dependencies

The Python code relies on the following libraries:

* NumPy
* SciPy
* Matplotlib

## Results and Visualizations

The repository includes visualizations of the simulation results, such as:

* Wavefunction evolution in time for Bloch oscillations.
* Wavefunction propagation in the Field-Flip System.
* Energy level distributions for the Angular Momentum and Pullen-Edmonds systems.
* Particle number dynamics for the Lindblad Master Equation.
* Tunneling dynamics and energy level structure for the Double Well Potential.
* Energy eigenvalues as a function of particle number for Bose-Hubbard model.

## Related Work

This project is based on the computational methods described in the following paper:

* Korsch, H. J., & Rapedius, K. (2010). Computations in quantum mechanics made easy. *European Journal of Physics*, *31*(6), 1291.

## Author

* Shaukat Aziz (IISc)
