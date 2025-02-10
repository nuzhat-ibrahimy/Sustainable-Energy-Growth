# Sustainable Energy Growth Forecasting

## Project Overview

The Sustainable Energy Growth Forecasting project aims to analyse global renewable electricity generation trends and forecast future growth using a deep learning model. By leveraging historical energy data and LSTM-based time series forecasting, this project provides insights to guide sustainable energy investments and policymaking.

## Objective

  - To predict future renewable electricity generation using LSTM (Long Short-Term Memory) networks.
    
  - To help investors, policymakers, and researchers make informed decisions regarding renewable energy expansion.
    
  - To provide a data-driven approach for assessing global and country-specific renewable energy trends.

## Dataset

The project uses the Global Data on Sustainable Energy (2000-2020) dataset, which includes renewable electricity generation figures for multiple countries and regions. This dataset helps train the LSTM model to understand historical energy trends and project future values.

This dataset is thanks to Ansh Tanwar from Kaggle; Tanwar, A. (2023). Global data on sustainable energy (2000-2020). Kaggle. https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy/data. https://doi.org/10.34740/KAGGLE/DSV/6327347

## Methodology

### Exploratory Data Analysis

  - Analyse the dataset’s features to understand trends and correlations.
  
  - Visualize historical renewable energy generation data.
    
### Data Preprocessing

  - Extract and clean renewable electricity data.
    
  - Normalise data for improved model performance.
    
### Model Training

  - Train an LSTM model to learn patterns in renewable electricity generation.

### Forecasting

  - Use the trained LSTM model to predict renewable electricity generation for the next several years.

  - Evaluate model performance using MAE (Mean Absolute Error), RMSE (Root Mean Squared Error), and Mean Absolute Percentage Error (MAPE)

## Project Structure
  - notebook/ → Contains the main Jupyter Notebook for data analysis, training, and forecasting.
  
  - models/ → Stores trained LSTM models for forecasting.
  
  - global-data-on-sustainable-energy (1).csv → The dataset used for training and predictions.
  
## Results & Insights

  - The model provides accurate multi-year forecasts for renewable energy generation.
    
  - Forecasts can be used to identify trends and make investment decisions.
    
## Future Improvements

  - Extend the model to forecast multiple energy sources (solar, wind, hydro, etc.).
    
  - Replace the dataset with the latest available data to improve forecast accuracy.
    
  - Improve hyperparameter tuning and fine-tune the LSTM model for better performance.
    
  - Develop an interactive dashboard for real-time forecasting.
    
  - Integrate additional economic and environmental factors for more comprehensive predictions.
    
