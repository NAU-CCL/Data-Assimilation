# **Particle Filter & Ensemble Kalman Filter for High-Dimensional SIR Model**  

This repository contains the implementation of **Particle Filter (PF) and Ensemble Kalman Filter (EnKF)** applied to the **Susceptible-Infected-Recovered (SIR) model** in **high-dimensional systems with movement dynamics**.

---

## 📌 **Overview**
In epidemiological modeling, tracking disease spread across multiple regions requires efficient state estimation methods. This project implements:
- **Particle Filter (PF)**: A Sequential Monte Carlo method for nonlinear, non-Gaussian state estimation.
- **Ensemble Kalman Filter (EnKF)**: A Kalman-based ensemble approach for tracking epidemic states.

The filters are applied to an **SIR model** with:
✔ **Spatial movement dynamics**  
✔ **Uncertainty quantification** using confidence intervals  
✔ **Infection rate ($( \beta )$) estimation over time**  
✔ **Comparison of filtering performance using RMSE**  

---

## 🛠 **Features**
✅ **Particle Filter (PF)**
- Uses **importance sampling** and **resampling techniques**.
- Works well with **nonlinear, non-Gaussian state-space models**.
- Provides **quantile-based uncertainty estimates**.

✅ **Ensemble Kalman Filter (EnKF)**
- Uses **ensemble-based state estimation** for large-scale problems.
- Computationally efficient for **high-dimensional systems**.
- Incorporates **stochastic perturbations for parameter tracking**.

✅ **Movement Model Integration**
- Tracks **infection spread across multiple locations**.
- Implements **mobility-based transmission dynamics**.

✅ **Visualization**
- Plots **infection rate (\( \beta \))** over time with:
  - **90% and 50% confidence intervals**.
  - **Median estimate vs. True infection rate**.
  - **RMSE-based filter performance evaluation**.

---

## 📂 **Repository Structure**
