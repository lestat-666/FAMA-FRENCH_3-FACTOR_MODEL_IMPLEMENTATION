# FAMA-FRENCH_3-FACTOR_MODEL_IMPLEMENTATION

## Overview
Advanced asset pricing and risk factor analysis using Python for quantitative portfolio attribution and performance measurement across equity securities.

## Key Features
- **CAPM Baseline Analysis**: Microsoft vs S&P 500 regression (R² = 0.534)
- **Enhanced CAPM**: Excess returns methodology improving model fit to R² = 0.948
- **Three-Factor Model**: Implementation of Fama-French model with Size (SMB) and Value (HML) factors
- **Real-World Application**: Analysis of Fidelity Growth Company Fund (FDGRX) achieving R² = 0.951

## Methodology
- Multi-source data integration: Yahoo Finance equity prices + Fama-French research database
- Time series alignment and data preprocessing using pandas
- Statistical modeling with statsmodels OLS regression
- Risk-adjusted performance attribution and factor analysis

## Key Results
- **Dramatic model improvement**: Basic CAPM (53.4%) → Enhanced CAPM (94.8%) → Three-Factor (95.1%)
- **Fund insights**: Identified positive alpha (0.64% monthly), growth orientation (HML = -0.44), and higher volatility (β = 1.15)
- **Statistical validation**: All factors significant at 95% confidence level

## Technologies
- **Python**: pandas, numpy, statsmodels, matplotlib, seaborn
- **Data Sources**: Yahoo Finance (yfinance), Fama-French Research Database
- **Analysis**: OLS regression, time series analysis, financial modeling
