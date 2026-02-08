# Stock Price Forecasting Using Time-Series and Regression Models

This repository contains a forecasting study analyzing historical stock prices from the energy sector and predicting short-term future prices using classical time-series techniques and regression-based models.

The project was completed in an Operations and Supply Chain Management course in Winter 2023 and focuses on practical forecasting methods used in industry decision-making.

---

## Project Overview

The analysis investigates daily closing prices for Exxon Mobil (XOM) during 2022 and applies two primary forecasting approaches:

- Holt’s double exponential smoothing  
- Linear regression with engineered features  

Before forecasting, the project evaluates:

- Trend and seasonality using ANOVA  
- Historical price patterns  
- External market factors influencing prices  
- Sensitivity of model parameters  

Multiple regression specifications were tested, including versions that incorporated additional causal variables from global energy markets.

---

## Repository Contents

- `README.md`
- `Stock_Price_Forecasting_Report.pdf`

- `forecasting_models/`
  - `anova_seasonality_tests.xlsx`  
  - `holt_exponential_smoothing.xlsx`  
  - `linear_regression_forecast.py`  

---

## Files

**Stock_Price_Forecasting_Report.pdf**  
Final written report describing assumptions, statistical tests, forecasting models, and business interpretation.

**anova_seasonality_tests.xlsx**  
ANOVA analysis examining weekly and monthly seasonality.

**holt_exponential_smoothing.xlsx**  
Implementation of Holt’s method with parameter optimization and error analysis.

**linear_regression_forecast.py**  
Python implementation of multi-feature regression forecasting models.

---

## Methods and Techniques

- Time-series analysis  
- Holt’s double exponential smoothing  
- Linear regression modeling  
- Feature engineering  
- Sensitivity analysis  
- Forecast error evaluation  
- Trend and seasonality testing  

---

## Tools and Technologies

- Python (pandas, numpy, scikit-learn)  
- Microsoft Excel (Solver and forecasting tools)  
- Statistical hypothesis testing  
- Financial time-series data  

---
