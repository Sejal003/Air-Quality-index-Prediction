# Air-Quality-index-Prediction

verview
This project implements a time series forecasting model to predict Air Quality Index (AQI) using Facebook Prophet. The model analyzes historical AQI data to forecast future air quality trends, helping in environmental monitoring and public health planning.
Dataset

**The project uses a CSV dataset containing historical AQI measurements. The data includes:**
Timestamp
AQI values
(Other relevant features in your dataset)

**Data Preprocessing**
Loading CSV data
Data cleaning
Handling missing values
Feature engineering
Time series formatting for Prophet

**Model Training**
Algorithm: Facebook Prophet
Time series decomposition
Trend and seasonality analysis
Model parameter tuning

**Features of FB Prophet Implementation**
Handles missing data automatically
Captures daily, weekly, and yearly seasonality
Accounts for holiday effects
Detects trend changes
Provides uncertainty intervals

**Results**
Model performance metrics
Visualization of predictions
Trend analysis
Seasonal patterns identified

**Usage**
pythonCopyfrom fbprophet import Prophet

**Initialize and train Prophet model**
model = Prophet()
model.fit(df)
Visualizations

**The project includes several visualizations:**
Historical AQI trends
Forecast predictions
Seasonal decomposition
Component analysis

