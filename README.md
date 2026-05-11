# quant-playground

## Overview

This project simulates multiple 1D random walks and explores their statistical properties. It demonstrates how simple stochastic processes lead to:

Mean reversion to zero
Growth of uncertainty over time
Emergence of the normal distribution

These ideas form the mathematical foundation of quantitative finance models such as Brownian Motion and Black–Scholes.

## Methodology
Each walk starts at 0
At each step: move +1 or -1 with equal probability
Simulate many independent walks

We then compute:

Mean path
Standard deviation over time
Distribution of final positions
Key Result

The standard deviation grows proportionally to:

σ(t) = √t

This matches theoretical predictions for random walks and diffusion processes.

## Visualisations

The project generates:

Multiple random walk paths
Mean path
Standard deviation vs √t comparison
Histogram of final positions

Mean stays near zero, showing symmetry
Spread increases over time, showing how uncertainty grows
Final positions follow a normal distribution


Random walks underpin:

Brownian Motion,
Geometric Brownian Motion,
Black–Scholes model

