# M5_Forecasting

## Overview
The M5 Forecasting project is an advanced initiative aimed at developing and implementing best practices for engineering time series data to enhance forecasting accuracy. This project leverages state-of-the-art methodologies and tools to address the complexities inherent in hierarchical forecasting, particularly in the context of the M5 competition.

## Purpose
The purpose of this project is to provide a comprehensive guide and set of tools for engineering time series data, with a focus on the following objectives:

Enhancing Forecast Accuracy: By employing advanced data engineering techniques, the project aims to improve the accuracy of time series forecasts. This includes preprocessing steps such as data cleaning, normalization, and transformation.
Standardizing Best Practices: Establishing a set of best practices for time series data engineering that can be adopted by the broader data science community. This includes guidelines on feature engineering, model selection, and evaluation metrics.
Facilitating Reproducibility: Ensuring that the methodologies and results are reproducible by providing detailed documentation, code examples, and datasets. This is crucial for validating the effectiveness of the proposed techniques and for enabling others to build upon this work.
Promoting Collaboration: Encouraging collaboration among data scientists, researchers, and practitioners by creating an open-source platform where contributions and feedback are welcomed.

## Data Preprocessing
Effective data preprocessing is critical for accurate time series forecasting. This project covers various preprocessing techniques, including:

Data Cleaning: Handling missing values, outliers, and inconsistencies in the data.
Normalization: Scaling the data to ensure that different features contribute equally to the model.
Transformation: Applying transformations such as log, differencing, and seasonal decomposition to stabilize the variance and make the series stationary.


## Feature Engineering
Feature engineering involves creating new features from the raw data that can help improve the model’s performance. Key techniques include:

Date-Time Features: Extracting features such as day of the week, month, and holiday indicators to incorporate calendar effects.
Lag Features: Creating lagged versions of the time series to capture temporal dependencies.
Rolling Statistics: Calculating rolling means, variances, and other statistics to smoothing data, capture trends and seasonality.
Trendline features: Creating fixed linear line from Linear Regression in aggregate by season in each product
Phasing ratio features: Creating contribution of index frequency in each seasonality.
Change point detection: Using ChangeFinder to tuning changepoint capture bend seasonality

## Model Selection
Selecting the right model is crucial for accurate forecasting. This project explores various models, including:

Statistical Models: SARIMA, ETS, VAR and Facebook Prophet.
Machine Learning Models: Linkedin Greykite, tree-based model.
Deep Learning Models: LSTM and Transformer-based models.

## Conclusion

The M5 Forecasting project is a comprehensive resource for anyone looking to improve their time series forecasting capabilities. By following the best practices outlined in this project, we cab enhance the accuracy and reliability of model forecasts. 

![image](https://github.com/user-attachments/assets/ec20068b-e2d0-4c9b-9e33-00d10650585e)
