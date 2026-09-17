[Uploading READMEmut.md…]()


# Multivariate Function Visualization & Parameter Estimation Project


This project focuses on **multivariate data analysis and statistical model estimation**, combining **numerical simulation and visualization techniques** to study parameter estimation problems in statistical models.

The research primarily investigates **parameter estimation in Normal Mixture Models** and **Maximum Likelihood Estimation (MLE) under constrained optimization problems**. Through simulated data and numerical methods, the study analyzes how parameter estimates behave under different sample sizes and model configurations. Visualization techniques are also used to help interpret model structures and optimization results.

---

# Project Overview

The project consists of two main parts:

1. **Parameter estimation in Gaussian Mixture Models**
2. **Constrained Maximum Likelihood Estimation and optimization visualization**

Both parts combine **statistical modeling, numerical computation, and graphical visualization** to better understand multivariate statistical problems.

---

# Part I: Gaussian Mixture Model Parameter Estimation

In the first part of the study, simulated data were generated from **Gaussian Mixture Distributions** under different parameter settings.

Two main scenarios were considered:

- **Close means** between the two normal components, producing a distribution that appears **unimodal**.
- **Well-separated means**, resulting in a clearly **bimodal distribution**.

The study examined how **sample size affects parameter estimation performance**.

---

## Estimation Methods

Two approaches were used to estimate the parameters of the mixture model:

- **Maximum Likelihood Estimation (MLE)**
- **Expectation–Maximization (EM) Algorithm** implemented using the `GaussianMixture` package

---

## Visualization and Comparison

To evaluate estimation accuracy, the following visualization tools were used:

- **Histograms of simulated data**
- **Probability Density Functions (PDF)**

The estimated distributions were compared with the **true underlying distribution** to analyze how different estimation methods and sample sizes affect the quality of parameter estimation.

---

# Part II: Constrained Maximum Likelihood Estimation

The second part of the project focuses on solving a **maximum likelihood estimation problem with parameter constraints** using **numerical optimization techniques**.

To improve numerical stability, the likelihood function was first transformed into a **log-likelihood function**.

---

## Visualization of the Optimization Landscape

To better understand the structure of the objective function, several visualization techniques were used:

- **3D Surface Plots**
- **Contour Plots**

These visualizations illustrate how the **log-likelihood function behaves in the parameter space**, helping identify potential optimal solutions.

---

## Numerical Optimization

After analyzing the parameter space visually, numerical optimization algorithms were applied to compute the **optimal parameter estimates**.

The results were then compared with the graphical analysis to verify the **consistency between visualization and numerical optimization results**.

---

# Key Findings

This project demonstrates how **statistical simulation, probabilistic modeling, and visualization techniques** can be combined to study multivariate statistical models.

Key insights include:

- The impact of **sample size on parameter estimation stability**
- The role of **model configuration in mixture model identification**
- The usefulness of **visualization techniques in understanding optimization problems**
- The consistency between **graphical analysis and numerical optimization results**

---

# Technologies Used

- Python
- NumPy
- SciPy
- scikit-learn
- Matplotlib
- Numerical Optimization Methods
- Statistical Simulation

---

# Key Topics

- Gaussian Mixture Models
- Maximum Likelihood Estimation (MLE)
- Expectation–Maximization (EM) Algorithm
- Constrained Optimization
- Multivariate Function Visualization
- Statistical Simulation
