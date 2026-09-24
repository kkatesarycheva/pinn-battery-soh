# pinn-battery-soh
Physics-informed neural network for battery state-of-health estimation from partial charge data
# Battery SOH Estimation with Physics-Informed Neural Networks

Estimating lithium-ion battery state-of-health (SOH) from short, partial
charge data using physics-informed neural networks (PINNs), aimed at
DIY solar/powerwall builders and small-scale second-life battery resellers
who currently rely on multi-hour full-cycle capacity testing.

Building on and extending Wang et al. (2024), *Nature Communications*,
"Physics-informed neural network for lithium-ion battery degradation
stable modeling and prognosis."

## Status
Early-stage research and prototyping. Starting point: reproducing the
published baseline on public datasets (XJTU, NASA, Oxford) before
extending to real-world/field data.

## Goal
A fast, uncertainty-quantified SOH estimator that doesn't require
full-cycle testing — trained on physics-constrained models rather than
black-box ML alone.
