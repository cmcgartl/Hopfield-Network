# Hopfield Neural Network – Storage Capacity & Noise Robustness Simulation

## Project Overview
- determines storage capacity and recall accuracy of a Hopfield Neural Network.
- Uses **Hebbian** and **Pseudo-inverse** learning
- Measures recognition of stored patterns with varying **noise** and **bias**.

## Features
- Genarates a binary pattern with customizable probability distribution of +1 or -1.
- Adds **bit-flip noise** and uneven probability distribution to test memory recall robustness.
- Graphs the number of overlaps vs. stored patterns using **matplotlib**
- Calculates storage capacity `α = L/S` with recall accuracy threshold ≥ 95%.

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

