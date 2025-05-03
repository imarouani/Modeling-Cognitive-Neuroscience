---

# Modeling-Cognitive-Neuroscience

**Adaptive Reinforcement Learning Models for Human Decision-Making in Reversal Tasks**

## Overview

This project implements and compares two reinforcement learning models to understand how humans adapt their decisions in dynamic environments. We modeled behavior in a probabilistic two-armed bandit task featuring a mid-task reward reversal, using both real and simulated data.

## Models

* **Rescorla-Wagner Model (RWM):** Uses a fixed learning rate for prediction-error-based value updating.
* **Bayesian Reinforcement Model (BRM):** Tracks uncertainty using Beta distributions and updates beliefs adaptively with a hazard rate.

## Dataset

* **Participants:** 11
* **Trials per participant:** 100
* **Task:** Two-armed bandit with reward probabilities reversing at trial 50 (80/20 → 20/80)

## Technical Contributions

* Implemented both RWM and BRM with softmax-based action selection
* Simulated agent behavior and reversal learning dynamics
* Fit models to real participant data using grid search over key parameters (α, β, λ)
* Visualized model behavior and fit quality using learning curves and likelihood surfaces
* Conducted model comparison using BIC and parameter recovery analyses
* Found that the RWM provided a better overall fit to participant behavior

## Tools & Libraries

* Python
* NumPy
* SciPy
* Pandas
* Matplotlib
* Seaborn

## Authors

This project was completed in collaboration with:
**David Raul Carranza Navarrete**, **Julian Calvin Rill**, **Franka Böckmann**, **Ewa Godlewska**, **Iheb Marouani**
