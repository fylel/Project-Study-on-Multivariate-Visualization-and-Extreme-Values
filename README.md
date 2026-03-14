# Monte Carlo Simulation for Normality Tests

This project investigates the statistical properties and performance of several **normality tests** using **Monte Carlo simulation**, with a primary focus on the **Jarque–Bera test**.

The study verifies whether the Jarque–Bera statistic follows its theoretical **Chi-square distribution** under normality and compares its performance with other widely used normality tests under different distributions and sample sizes.

---

# Project Objectives

The primary goals of this project are:

- Verify the **theoretical Chi-square distribution** of the Jarque–Bera statistic.
- Analyze the **distributional behavior of skewness and kurtosis-based statistics**.
- Compare the **performance and statistical power** of multiple normality tests.
- Evaluate how well different tests **detect non-normal distributions**.

---

# Methodology

## Monte Carlo Simulation

Large-scale **Monte Carlo simulations** were conducted to analyze the statistical properties of normality test statistics.

Simulations were performed under varying **sample sizes** to investigate how the distribution of the Jarque–Bera statistic behaves as sample size increases.

---

## Distributional Analysis

The study examined statistics constructed from **sample skewness and kurtosis**, which form the basis of the Jarque–Bera test.

The empirical distribution of the test statistic was analyzed using:

- **Histograms**
- **Empirical Cumulative Distribution Functions (Empirical CDF)**

These results were compared with the theoretical **Chi-square distribution** to evaluate their goodness-of-fit.

---

## Implementation of the Jarque–Bera Test

A custom implementation of the **Jarque–Bera test** was developed.

The function computes:

- **Jarque–Bera test statistic**
- **p-value based on the Chi-square distribution**

This implementation was used in subsequent simulation experiments and compared with the implementation available in the **SciPy library**.

---

# Comparison of Normality Tests

To evaluate practical performance, several commonly used normality tests were compared:

- **Jarque–Bera Test**
- **Shapiro–Wilk Test**
- **Anderson–Darling Test**
- **SciPy Jarque–Bera Implementation**

---

## Evaluation Criteria

The tests were evaluated based on the following criteria:

### Type I Error Control
Whether the test maintains the nominal significance level under normality.

### Statistical Power
The ability of the test to detect deviations from normality.

---

# Experimental Settings

The simulations were conducted under multiple underlying distributions:

- **Normal Distribution**
- **t-Distribution**
- **Uniform Distribution**
- **Chi-square Distribution**

Different **sample sizes** were considered to analyze how test performance varies with increasing data size.

---

# Results and Insights

Monte Carlo simulation results reveal differences in how various normality tests perform across different scenarios.

Key observations include:

- The **Jarque–Bera statistic** approaches the theoretical **Chi-square distribution** as the sample size increases.
- Different tests exhibit **different levels of sensitivity** to skewness and kurtosis.
- Some tests perform better under specific **non-normal distributions**.

These results provide insights into the **comparative performance and applicability** of different normality tests in statistical inference.

---


