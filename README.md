# Air Quality Prediction using Machine Learning

This project uses a machine learning model to predict air quality based on pollutant features like SO2, NO2, RSPM, and SPM.

## 📂 Dataset
The dataset used in this project is named `data` and comes from [Central Pollution Control Board, India (Open Data)](https://data.gov.in/), which provides air quality data across various regions of India.

## 📊 Features Used
The features used in the model include:
- so2: Sulfur Dioxide concentration.
- no2: Nitrogen Dioxide concentration.
- rspm: Respirable Suspended Particulate Matter.
- spm: Suspended Particulate Matter.

## ✅ Models Implemented
The following machine learning models were implemented:
- **Linear Regression**: A basic model for predicting continuous values.
- **Random Forest Regressor**: A more complex model that gave better performance for this project.

## 📈 Evaluation Metrics
The performance of the models was evaluated using:
- **Mean Squared Error (MSE)**: Measures how close the predictions are to the actual values.
- **R-squared (R²)**: A statistic that indicates how well the model fits the data.

## 📌 Results
- The **Random Forest Regressor** performed better than the Linear Regression model in predicting air quality.

## 📁 Files
- `air_quality_prediction.ipynb`: The main Colab notebook containing the code and results.
- `README.md`: This file, explaining the project.
