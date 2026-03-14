# Volatility Forecast Combination

## Overview

This project explores forecast combination methods for financial volatility prediction using time-series models. The objective is to improve forecasting accuracy during periods of market uncertainty by combining information from multiple volatility models.

## Project Status

This project is currently under development as part of my honours research on volatility forecasting and forecast combination methods. The repository will be updated regularly as new experiments, models, and results are completed.

## Methods

The modelling framework is based on the Heterogeneous Autoregressive (HAR) model, a commonly used approach for capturing long-memory dynamics in financial volatility. This project implements forecast combination techniques to integrate predictions from multiple econometric specifications.

Model performance is evaluated using several standard forecasting metrics, including Mean Squared Error (MSE) and QLIKE loss.

## Dataset

The analysis uses publicly available U.S. equity market data from 2000–2025. The dataset includes daily realized volatility for two major indices (Dow Jones Industrial Average and S&P 500) as well as the top 30 individual stocks in the sample.

## Results

The empirical analysis is currently under development. Preliminary experiments suggest that forecast combination methods may improve volatility prediction accuracy relative to individual HAR model specifications across several evaluation metrics, including MSE and QLIKE. Further analysis will evaluate performance across different assets and forecasting horizons.

## Future Work

- Implement additional forecast combination schemes
- Compare performance across different volatility models
- Evaluate robustness across alternative time horizons

## Technologies

Python  
Pandas  
NumPy  
Statsmodels  
Matplotlib
