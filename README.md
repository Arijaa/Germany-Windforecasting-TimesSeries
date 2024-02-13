# Time Series Wind Project in Germany 🌬️

## Overview
This repository contains code for a time series wind project focused on predicting wind energy generation in Germany. The project aims to forecast wind power generation using historical weather data and other relevant features.

## Data
The dataset used in this project includes historical records of wind speed, direction, temperature, humidity, and other meteorological variables. The data covers a span of several years and is sourced from reputable weather stations across Germany.

## Models

### 1. ARIMA (Autoregressive Integrated Moving Average)
- ARIMA is a classic time series forecasting model that utilizes autoregression and moving average components. It is suitable for stationary time series data.
- We applied ARIMA to the wind power generation data, adjusting parameters such as order (p, d, q) to optimize model performance.

### 2. LSTM (Long Short-Term Memory)
- LSTM is a type of recurrent neural network (RNN) architecture designed to handle sequence prediction problems.
- In our project, we implemented LSTM to capture long-term dependencies and patterns in the time series data. This model proved effective in capturing complex temporal dynamics inherent in wind energy generation.

### 3. Prophet
- Prophet is an open-source forecasting tool developed by Facebook that is widely used for time series analysis.
- We experimented with Prophet to model the seasonal trends and holidays in the wind power generation data. Its flexibility and ease of use make it suitable for rapid prototyping and model iteration.

### 4. XGBoost (Extreme Gradient Boosting)
- XGBoost is an ensemble learning algorithm known for its speed and performance in handling structured data.
- We employed XGBoost to build a gradient boosting model for wind power generation prediction. It proved effective in capturing non-linear relationships and feature interactions in the dataset.


## Conclusion
Predicting wind power generation is crucial for efficient energy management and planning. By leveraging time series forecasting models such as ARIMA, LSTM, Prophet, and XGBoost, we can accurately predict wind energy output, aiding in renewable energy integration and grid stability. This project demonstrates the effectiveness of machine learning and statistical techniques in addressing real-world energy challenges.

Feel free to explore the code and models in this repository to gain insights into wind energy forecasting in Germany.
