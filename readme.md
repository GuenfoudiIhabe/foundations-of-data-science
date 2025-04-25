# Healthcare Data Analysis Foundations

This repository contains a series of homework assignments exploring healthcare data analysis, focusing on pulse oximetry and heart failure prediction using Bayesian methods and statistical modeling techniques.

## Overview

The assignments progressively build skills in healthcare data analysis:

1. **Data Exploration**: Understanding pulse oximetry data
2. **Statistical Inference**: Building models to infer oxygen saturation from PPG signals
3. **Bayesian Methods**: Implementing MCMC sampling for parameter estimation
4. **Survival Analysis**: Predicting heart failure using Cox proportional hazard models

## Assignments

### HW1: Exploration of Pulse Oximetry Data

**File:** `hw1-data-exploration/hw1.ipynb`

This introductory assignment focuses on:
- Loading and cleaning data from the OpenOximetry Repository
- Computing descriptive statistics and visualizing correlations
- Analyzing oxygen saturation measurements across patient encounters
- Visualizing PPG signals alongside oxygen saturation data

### HW2: Inference of Oxygen Saturation from Photoplethysmography

**File:** `hw2-spo2-inference/hw2.ipynb`

Building on HW1, this assignment covers:
- Implementing a probabilistic model relating SpO₂ to PPG signals
- Computing the ratio of normalized pulsative components
- Applying maximum likelihood estimation to infer oxygen saturation
- Comparing empirical models with MLE-based approaches

### HW3: Bayesian Inference with MCMC

**File:** `hw3-mcmc/hw3.ipynb`

This advanced assignment explores:
- Implementing the full Bayesian workflow for oxygen saturation inference
- Defining prior distributions for model parameters
- Sampling from posterior distributions using MCMC
- Evaluating model performance through posterior predictive checks

### HW4: Heart Failure Prediction

**File:** `hw4-heart-failure/hw4.ipynb`

The final assignment applies survival analysis to heart failure data:
- Implementing Cox proportional hazard models
- Building probabilistic graphical models for survival analysis
- Performing Bayesian inference on model parameters
- Evaluating model fit and interpretability

## Technologies Used

- Python 3
- Libraries: NumPy, Pandas, Matplotlib, Seaborn
- Statistical libraries: SciPy, Emcee (MCMC)
- Medical data analysis: WFDB (for reading waveform data)


## Acknowledgments

This work was completed as part of the Foundations of Data Science course taught by Giles Loupe.
- Course GitHub: https://github.com/glouppe/dats0001-foundations-of-data-science