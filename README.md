# Forecasting Time Series: A Practical Walkthrough

This [notebook](forecast.ipynb) presents a structured approach to time series forecasting using daily retail sales data from a grocery chain in Ecuador (Kaggle's Store Sales competition). The goal is to build accurate and interpretable forecasting models by progressively incorporating trend, seasonality, lagged features, and hybrid modeling techniques.

## Overview

The notebook covers the following:

- Modeling trend using moving averages and polynomial regression
- Capturing seasonal patterns with indicator variables and Fourier features
- Using lagged features and exogenous variables to model serial dependence
- Accounting for holiday effects using external regressors
- Combining models (e.g. Linear Regression and XGBoost) for better performance
- Building multi-step forecasts with the DirRec strategy

## Dataset

The data includes:

- Daily sales for multiple product families across several stores
- Promotion flags
- National and regional holidays

The dataset contains clear patterns in trend, seasonality, and cyclic behavior, making it well-suited for time series modeling.

## Tools and Libraries

- Python (pandas, numpy, matplotlib, seaborn)
- statsmodels (DeterministicProcess, Fourier terms)
- scikit-learn (LinearRegression, pipelines)
- XGBoost (nonlinear modeling)
- RegressorChain (for multi-step forecasting)

## Structure

The notebook progresses in stages, starting from basic trend modeling and moving toward more advanced feature engineering and modeling techniques. Each section includes code, visualizations, and explanations to support both learning and practical implementation.

---

This project is intended as both a learning resource and a template for building production-ready forecasting pipelines.

[Open the notebook](forecast.ipynb)
