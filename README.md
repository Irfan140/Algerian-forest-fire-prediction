# Algerian Forest Fire Prediction - Multiple Regression

This repository contains a Machine Learning project focused on predicting the Fire Weather Index (FWI) based on environmental factors using multiple regression. The dataset used for this project is the **Bejaia Region Fire Dataset**. It includes data about forest fires in the Bejaia region of Algeria, covering factors such as temperature, humidity, wind speed, rainfall, and several fire danger indices. The goal of this project is to apply multiple regression techniques to predict the FWI, which can help in understanding the severity of potential forest fires and support fire management efforts.


## Project Overview

The project involves:
- **Data Exploration**: Analyzing the dataset by examining the variables and performing necessary data cleaning.
- **Feature Selection**: Identifying key environmental factors influencing the Fire Weather Index (FWI).
- **Model Training**: Applying multiple regression techniques to build a predictive model for FWI based on selected features.
- **Model Evaluation**: Assessing the model's performance using metrics like R-squared and Mean Squared Error (MSE).

The aim is to predict the FWI and provide insights into how environmental variables contribute to fire weather conditions.

## Dataset

The **Bejaia Region Fire Dataset** consists of daily records with various meteorological and fire-related factors for the Bejaia region, Algeria. The dataset contains the following key variables:

- **Temperature (°C)**: The daily average temperature.
- **RH (%)**: The daily relative humidity.
- **Wind Speed (km/h)**: The daily wind speed.
- **Rainfall (mm)**: The daily rainfall measurement.
- **FFMC**: Fine Fuel Moisture Code (a fire danger index).
- **DMC**: Duff Moisture Code (a fire danger index).
- **DC**: Drought Code (a fire danger index).
- **ISI**: Initial Spread Index (a fire danger index).
- **BUI**: Build-up Index (a fire danger index).
- **FWI**: Fire Weather Index (the target variable to predict).
- **Classes**: Fire occurrence status (`fire` or `not fire`).

The dataset is publicly available and can be accessed from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Forest+Fires).


