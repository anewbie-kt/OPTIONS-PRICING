# Final Project: Asian Paints Option Pricing using Deep Learning

This folder contains the **final capstone project** completed during the **Winter School of Data Science (WiDS) 2025**.  
The project applies data science and deep learning techniques to a real-world financial problem: **pricing stock options for Asian Paints**.

---

## Project Overview
- Dataset: NSE single-stock options on Asian Paints
- Time period: 2017–2020
- Objective: Learn a data-driven option pricing function using neural networks

---

## Models Implemented

### MLP1 — Single-Task Model
- Predicts equilibrium option price
- Multi-layer perceptron with three hidden layers
- Uses financial feature engineering for stable training

### MLP2 — Multi-Task Model
- Predicts bid and ask prices simultaneously
- Equilibrium price recovered as average of bid and ask
- Demonstrates benefits of multi-task learning

---

## Key Steps
- Data cleaning to remove expiry-day and stale-price rows
- Feature engineering (moneyness, volatility, time to expiry)
- Model training and evaluation using MSE/RMSE
- Analysis of results using plots and error breakdowns

---

## Learning Outcomes
- Working with noisy real financial datasets
- Importance of feature engineering over raw inputs
- Understanding neural network training dynamics
- Applying deep learning concepts to finance

This project integrates concepts learned throughout WiDS into a single end-to-end application.
