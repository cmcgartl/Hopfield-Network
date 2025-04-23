# Hopfield Neural Network – Storage Capacity & Noise Robustness Simulation

## Project Overview
- Simulates a **Hopfield associative memory model** to evaluate storage capacity and recall accuracy.
- Implements: **Hebbian** and **Pseudo-inverse**.learning
- Measures how well stored patterns are recalled under **noise** and **bias**.

## Features
- Supports **bipolar pattern generation** (`+1/-1`) with customizable probability distribution.
- Evaluates convergence behavior of the network across **100 neurons** and up to **100 patterns**.
- Adds optional **bit-flip noise** to test robustness of memory recall.
- Visualizes results with **matplotlib**: overlap vs. number of stored patterns.
- Calculates storage capacity `α = L/S` where recall accuracy ≥ 95%.

## Key Experiments
- Hebbian learning with clean patterns.
- Pseudo-inverse learning with clean patterns.
- Pattern recall with:
  - **Biased pattern distribution** (+1 probability = 0.75)
  - **Noisy input patterns** (20% bits flipped)

## Tech Stack
- **Python 3**
- **NumPy** for matrix computations
- **Matplotlib** for plotting

