# Indoor Air Quality Monitoring System

This repository showcases a project on developing an **IoT-based indoor air quality monitoring system**. The project, completed as part of the **DSAI3204 IoT Application Development** course at **Qatar University**, utilizes an **Arduino MKR1010** to collect environmental data and perform predictive analysis using machine learning.

---

## Project Overview

The primary goal of this project was to **design, build, and analyze a system** for monitoring indoor air quality. The system:

- Measures real-time **temperature** and **CO₂ levels**
- Logs the data to a **cloud service**
- Applies **machine learning models** to analyze trends and forecast future values

---

## Technologies Used

- **Hardware**: Arduino MKR1010, Temperature Sensor, CO₂ Sensor  
- **Programming Languages**: Python, Arduino (C++)  
- **Libraries & Frameworks**:  
  - `pandas`, `NumPy`, `scikit-learn`, `statsmodels`  
  - `XGBoost`, `LightGBM`  
- **Data Analysis**: Jupyter Notebook

---

## Repository Contents

- **`data_extraction.ipynb`**  
  Extracting Data from arduino.

- **`main.ipynb`**  
  Main notebook containing advanced analysis and implementation of machine learning models for time-series forecasting.

- **`report.docx`**  
  Final report detailing system design, methodology, results, and conclusions.

---

## Key Features

###  Data Acquisition

- Real-time collection of environmental data (temperature and CO₂)
- Integration with Arduino MKR1010 and sensors
- Cloud-based logging for remote access and analysis

###  Data Analysis

- Conducted **Exploratory Data Analysis (EDA)**
- Applied **time-series decomposition** to extract trend, seasonality, and residuals

###  Machine Learning Models

- Implemented multiple models for forecasting:
  - **SARIMAX** (Seasonal ARIMA with eXogenous variables)
  - **XGBoost** (Extreme Gradient Boosting)
  - **LightGBM** (Light Gradient Boosting Machine)

### Model Evaluation

- Evaluated models using:
  - **Root Mean Squared Error (RMSE)**
  - **Mean Absolute Error (MAE)**

---
