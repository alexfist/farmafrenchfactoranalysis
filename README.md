# farmafrenchfactoranalysis
# Fama-French Factor Analysis

## Overview
Implementation of the Fama-French 3-factor model analyzing return drivers 
across 15 stocks using Python and OLS regression.

## Motivation
The Fama-French model extends CAPM by adding size (SMB) and value (HML) 
factors to better explain cross-sectional stock returns. This project 
empirically tests the model on a diverse portfolio of stocks.

## Methodology
- Downloaded factor data from Kenneth French's data library
- Calculated monthly excess returns for 15 stocks across sectors
- Ran OLS regressions to estimate factor loadings and alphas
- Analyzed rolling betas to examine factor exposure over time

## Results
*(To be updated as analysis progresses)*

## Technologies
Python, pandas, numpy, statsmodels, matplotlib, seaborn, yfinance

## Data Sources
- [Kenneth French Data Library](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html)
- Yahoo Finance via yfinance
