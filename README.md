# Molten-Salt-Fast-Reactor-Simulation
This project models a Molten Salt Fast Reactor (MSFR) and provides tools for comprehensive analysis and prediction, including:

- Linear stability analysis
- Non-linear time-domain modeling
- System control modeling
- Machine learning prediction

## Stability Analysis

We analyze the eigenvalues of the MSFR dynamic matrix to assess system stability
under variations of:

- Fuel temperature feedback (α_fuel)
- Mass flow rate
- Reactor power

## Non-Linear Model
Time-domain simulation of reactor dynamics including:

- Delayed neutron groups
- Temperature feedback
- Circulating fuel effects

## System Control
Basic control strategies for regulating reactor behavior.

## Machine Learning Prediction
Exploration of ML techniques for predicting reactor state evolution.

## Governing Physics

The model includes standard reactor kinetics parameters:

- Delayed neutron fractions (βᵢ)
- Decay constants (λᵢ)
- Neutron generation time (Λ)
- Temperature reactivity feedback (αₜ)

## Dependencies

- numpy
- scipy
- matplotlib
- scikit-learn (if ML section used)

