# IndiaRadiationML
Comparative Analysis of Tree-Based Ensembles and Neural Networks for Solar Radiation Prediction Across Major Indian Cities.
This repository provides the code and data for a comprehensive study comparing tree-based ensemble learning methods (Random Forest, XGBoost) and deep neural networks (LSTM, RNN) for daily solar radiation prediction. The analysis uses a five-year, multi-city dataset from Delhi, Mumbai, Chennai, and Kolkata, representing India's diverse climate zones.

## Project Highlights

Objective: Evaluate and compare the accuracy, interpretability, and computational efficiency of leading machine learning models for solar radiation forecasting.

Dataset: 7,305 daily meteorological records (2020–2024) from four major Indian cities, including features like temperature, humidity, wind speed, precipitation, and surface solar radiation.

## Models Implemented:

Random Forest Regressor

XGBoost Regressor

LSTM Neural Network

Simple RNN Neural Network

## Key Findings:

Tree-based ensemble methods (especially Random Forest) consistently outperform neural networks in accuracy (MAE, RMSE, R²), robustness, and computational efficiency for moderate-sized, multi-regional meteorological datasets.

Random Forest achieved the lowest MAE (0.707), RMSE (0.929), and highest R² (0.599) across all cities.

Temperature and humidity are the most influential predictors of solar radiation.

Ensemble methods are more robust to missing data, regional variability, and require less training time than deep learning models.

Feature Importance: Tree-based models provide clear feature importance rankings, supporting scientific interpretability and operational trust.

Reproducibility: All code and processed datasets are included for full reproducibility and further research.


