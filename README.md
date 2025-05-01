# final_project_ml
Final ML Project

# 🛒 Retail Sales Forecasting with Random Forest & Linear Regression

This project forecasts daily retail sales using machine learning. The dataset includes multiple stores and items over time. The workflow covers data preprocessing, time-based feature engineering, model training (Random Forest & Linear Regression), evaluation with SMAPE and MAE, and result visualization.

---

## 📌 Key Features

- 🧼 Data preprocessing & log transformation
- 📆 Time-based feature engineering (month, weekday, quarter, season)
- 🌲 Forecasting with **Random Forest**
- 📈 Benchmarking with **Linear Regression**
- 📉 Evaluation using SMAPE and MAE
- 🔁 Simple model ensembling
- 📊 Seasonal decomposition visualization

---

## 📁 Project Structure

Retail-Sales-Forecasting/ │ ├── df_train.csv # Training dataset ├── df_test.csv # Test dataset ├── submission_random_forest.csv # Final predictions ├── script.ipynb / .py # This code script ├── README.md └── requirements.txt

---

## 🧪 Models Used

- **Random Forest Regressor**  
- **Linear Regression**  
- **Simple Ensemble** (average of both)

All models are trained on time-encoded features and evaluated using:
- **SMAPE** (Symmetric Mean Absolute Percentage Error)
- **MAE** (Mean Absolute Error)

---

## ⚙️ Requirements

Required Packages:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- statsmodels

## 🚀 How to Run
Make sure df_train.csv and df_test.csv are in your working directory.

Run the full script or notebook to:

Load & preprocess the data

Train models

Evaluate performance

Generate submission file




