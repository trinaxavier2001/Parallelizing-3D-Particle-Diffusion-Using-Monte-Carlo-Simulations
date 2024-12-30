# Parallelizing-3D-Particle-Diffusion-Using-Monte-Carlo-Simulations
## Overview
This project models 3D particle diffusion using Monte Carlo simulations, solving the diffusion equation by simulating random particle movements. By leveraging GPU acceleration, the project achieves a 49x speedup over CPU execution, making large-scale simulations computationally feasible. Analytical validation ensures the accuracy of results.

## Features
Monte Carlo Simulation: Stochastic modeling of particle diffusion in 3D.
GPU Acceleration: Parallelized computations using CuPy for significant speedups.
Scalable: Adjustable parameters for grid size, particle count, and simulation complexity.
Visualization: 3D visualizations of diffusion behavior using Matplotlib.

## Skills & Tools
Programming Languages: Python
Libraries: CuPy, Matplotlib, NumPy
Concepts: Parallel Computing, Monte Carlo Methods, Diffusion Equation
Hardware: GPU acceleration (NVIDIA Tesla T4)

## Real-World Applications
Environmental Science: Predicting pollutant dispersion in ecosystems.
Healthcare: Modeling drug delivery or biological transport mechanisms.
Engineering: Simulating material stress, heat diffusion, or corrosion.

## Key Results
Performance: 49x speedup achieved through GPU parallelization.
Accuracy: Mean squared error ~10⁻¹², closely matching analytical solutions.
Efficiency: Simulation time reduced from ~1000 seconds (serial CPU) to ~22 seconds (parallel GPU).
