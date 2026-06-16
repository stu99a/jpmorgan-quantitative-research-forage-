# JPMorgan Chase Quantitative Research Virtual Experience Program

This repository contains solutions developed as part of the JPMorgan Chase Quantitative Research Virtual Experience Program hosted on Forage.

## Project Overview

The project focuses on applying quantitative research and machine learning techniques to real-world financial problems including:

* Commodity price forecasting
* Natural gas storage contract valuation
* Credit risk modelling
* FICO score quantization and risk bucketing

## Task 1 – Natural Gas Price Forecasting

Developed a forecasting model using trend and seasonal components to estimate historical and future natural gas prices.

Key techniques:

* Time series analysis
* Linear regression
* Seasonal feature engineering
* Daily interpolation

## Task 2 – Storage Contract Valuation

Built a valuation engine for natural gas storage contracts incorporating:

* Injection and withdrawal schedules
* Capacity constraints
* Storage costs
* Forecasted commodity prices

## Task 3 – Probability of Default (PD) Model

Constructed a logistic regression model to estimate borrower default risk using:

* Credit exposure metrics
* Employment history
* Income
* FICO scores

The model achieved excellent predictive performance with a ROC-AUC close to 1.0 on the provided dataset.

## Task 4 – Credit Rating Bucketing

Implemented a FICO score quantization framework to transform continuous credit scores into categorical risk ratings.

The resulting rating system demonstrates a monotonic relationship between borrower ratings and probability of default.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Jupyter Notebook

## Disclaimer

This repository contains educational solutions created as part of the JPMorgan Chase Quantitative Research Virtual Experience Program and is intended solely for learning and portfolio purposes.
