# **Asset pricing**

This repository contains Python scripts for portfolio optimization, asset pricing, and behavioral analysis using financial models. These scripts utilize advanced techniques to explore efficient frontiers, stochastic discount factors, risk-adjusted performance metrics, and investor behavior under utility-based frameworks.

---

## **Contents**

1. [HW1. Efficient Frontier](#hw1-efficient-frontier)
2. [HW2. SML, CAPM](#hw2-sml-capm)
3. [HW3. Sharpe, Treynor, Sortino, Jensen's a](#hw3-sharpe-treynor-sortino-jensens-a)
4. [HW4. Min Tracking Error Frontier](#hw4-min-tracking-error-frontier)
5. [HW5. Stochastic Discount Factor](#hw5-stochastic-discount-factor)
6. [HW6. Behavioral Finance](#hw6-behavioral-finance)

---

### **HW1. Efficient Frontier**

This script demonstrates the construction of an **efficient frontier** and **tangency portfolio** using mean-variance optimization. 

#### Features:
- Calculates mean returns, covariance matrix, and Sharpe ratio.
- Constructs efficient frontiers with and without a risk-free asset.
- Visualizes risk-return trade-offs.

#### Outputs:
- Efficient frontier plots.
- Tangency portfolio weights and Sharpe ratio.

---

### **HW2. SML, CAPM**

This script applies the **Capital Asset Pricing Model (CAPM)** to estimate alpha and beta for ten industry portfolios and constructs the **Security Market Line (SML)**.

#### Features:
- Estimates alpha (\( \alpha \)) and beta (\( \beta \)) using regression.
- Visualizes the SML and portfolio positions.
- Analyzes overperformance and underperformance against CAPM.

#### Outputs:
- Alpha and beta values.
- SML plot showing portfolio risk-return positions.

---

### **HW3. Sharpe, Treynor, Sortino, Jensen's a**

This script evaluates portfolios using **Sharpe**, **Treynor**, and **Sortino ratios**, alongside Jensen's alpha and Fama-French three-factor model.

#### Features:
- Calculates risk-adjusted metrics for ten portfolios.
- Evaluates alpha contributions from size and value factors.
- Visualizes performance metrics for easy comparison.

#### Outputs:
- Risk-adjusted performance table.
- Bar charts for metrics such as Sharpe and Sortino ratios.

---

### **HW4. Min Tracking Error Frontier**

This script focuses on the **minimum-tracking-error frontier** using deviations from market returns and includes **Monte Carlo simulations** for minimum-variance portfolios.

#### Features:
- Constructs minimum-tracking-error frontiers.
- Derives tangency portfolio weights and information ratios.
- Simulates efficient frontiers with and without short sales.

#### Outputs:
- Minimum-tracking-error frontier plots.
- Monte Carlo simulation scatter plots for risk-return trade-offs.

---

### **HW5. Stochastic Discount Factor**

This script explores the **stochastic discount factor** (pricing kernel) under a lognormal consumption growth model, accounting for rare disasters.

#### Features:
- Simulates consumption growth under disaster scenarios.
- Analyzes risk-return trade-offs for varying levels of relative risk aversion (\( \gamma \)).
- Plots the Sharpe ratio (\( \sigma_M / \mu_M \)) against \( \gamma \).

#### Outputs:
- Consumption growth simulations.
- Sharpe ratio plot with insights on investor risk preferences.

---

### **HW6. Behavioral Finance**

This script models investor behavior under the **Barberis, Huang, and Santos framework**, incorporating loss aversion and varying risk preferences.

#### Features:
- Solves equilibrium for price-dividend ratios using bisection search.
- Evaluates equity premiums as a function of sensitivity to consumption.
- Captures loss aversion and house money effects.

#### Outputs:
- Price-dividend ratio and equity premium plots.
- Behavioral insights into investor sensitivity to losses and gains.

---
