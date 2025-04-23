# COVID-19 Epidemic Forecasting Models - SIR Hybrid Models

This repository contains the implementation of various **SIR Hybrid Models** for forecasting COVID-19 infections. The project integrates classical epidemiological models (SIR) with machine learning techniques (LSTM and Regression) to predict the spread of COVID-19 at both national and district levels in Sri Lanka. The models aim to combine the strengths of traditional models and machine learning for accurate, interpretable epidemic forecasting.


This contains the implementation of the **Hybrid SIR Models**:
- **Hybrid SIR-Regression Models ISLAND WIDE**: Combines the SIR model with regression techniques (linear, polynomial, and logarithmic) to predict future infections.
- **Hybrid SIR-LSTM Model ISLAND WIDE**: Integrates the SIR model with a Long Short-Term Memory (LSTM) network for enhanced short-term forecasting.
- **Hybrid SIR-Regression Models DISTRICT WISE**: Combines the SIR model with regression techniques (linear, polynomial, and logarithmic) to predict future infections.
- **Hybrid SIR-LSTM Model DISTRICT WISE**: Integrates the SIR model with a Long Short-Term Memory (LSTM) network for enhanced short-term forecasting.
  

### dataset
This directory contains:
- **sri_lanka_covid19_data.csv**: The dataset used for training and validating the forecasting models. It includes daily records of COVID-19 infections, recoveries, deaths, and population statistics from Sri Lanka.
- **disdrict distribution 2020-2021.csv**: The dataset used for training and validating the forecasting models. It includes daily records of COVID-19 infections, recoveries, deaths, and population statistics from Sri Lanka.
- **data_preprocessing.py**: Preprocessing script for handling missing values, normalization, and feature engineering necessary for model training.

### lstm_predictions_output
This folder includes:
- **lstm_predictions_results.csv**: The output of the Hybrid SIR-LSTM model with predicted infection counts.
- **lstm_predictions_analysis.py**: Analysis of the LSTM model predictions, including performance metrics and comparison with actual infection data.

### regression_predictions_output
This folder includes:
- **regression_predictions_results.csv**: The output of the Hybrid SIR-Regression model with predicted infection counts.
- **regression_predictions_analysis.py**: Analysis of the Regression model predictions, including performance metrics and comparison with actual infection data.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/COVID-19-forecasting.git
