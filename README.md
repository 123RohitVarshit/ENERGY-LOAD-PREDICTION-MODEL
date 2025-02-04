# ENERGY-LOAD-PREDICTION-MODEL
# Energy Load Prediction using SARIMA  

This repository contains an implementation of **Energy Load Prediction** using the **SARIMA (Seasonal AutoRegressive Integrated Moving Average) model** for time series forecasting. The project aims to analyze past energy consumption data and predict future load demand with high accuracy.  

## 📌 Project Overview  

Accurate energy load forecasting is crucial for power grid management, optimizing energy distribution, and reducing operational costs. This project leverages the **SARIMA model**, a powerful time series forecasting technique, to make reliable future load predictions.  

## 🛠 Features  

- **Time Series Analysis**: Preprocessing and visualization of historical energy load data.  
- **SARIMA Model Implementation**: Applying the SARIMA model to capture seasonality, trends, and autoregressive patterns.  
- **Hyperparameter Tuning**: Selecting the optimal (p, d, q) and (P, D, Q, s) values for model performance using autoarima function. 
- **Model Evaluation**: Assessing prediction accuracy using metrics such as RMSE and MAPE.  
- **Future Forecasting**: Generating predictions for upcoming energy load demand.  

## 📂 Dataset  

The dataset consists of historical energy consumption records, including:  

- **Timestamp** (Hourly/Daily/Monthly)  
- **Energy Load** (kWh or MW)  

## 🚀 Installation  

Clone the repository and install the required dependencies:  

```bash
git clone https://github.com/123RohitVarshit/ENERGY-LOAD-PREDICTION-MODEL.git
cd ENERGY-LOAD-PREDICTION-MODEL
pip install -r requirements.txt
