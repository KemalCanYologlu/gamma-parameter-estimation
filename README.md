# Point Estimation of Gamma Distribution Parameters

This repository contains the STAT 303 (Mathematical Statistics I) term project,
which compares **Method of Moments (MoM)** and **Maximum Likelihood Estimation (MLE)**
for estimating Gamma distribution parameters.

## Project Overview
- Distribution: Gamma(k, θ)
- Estimation methods: MoM and MLE
- Approach:
  - Theoretical derivations
  - Estimation on simulated data
  - Extensive Monte Carlo simulation studies

## Simulation Design
- Scenarios with different skewness levels
- Sample sizes: n = 20, 50, 100
- Performance metrics:
  - Bias
  - Variance
  - Mean Squared Error (MSE)

## Key Findings
- MLE consistently outperforms MoM in terms of MSE
- Performance gap is larger under high skewness
- MoM remains a useful and simple alternative for large samples

## Tools
- R (simulation, estimation, visualization)

## Academic Context
This project was completed as part of **STAT 303 – Mathematical Statistics I**
at Middle East Technical University.

📄 Full report is available in the `report/` folder.
