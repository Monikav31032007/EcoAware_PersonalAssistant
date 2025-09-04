Eco-Aware Personal Assistant
Project Objective

Develop an AI/ML system that monitors air pollution, analyzes environmental data, and provides eco-friendly suggestions.
___________________________________________________________________________________________________
Project Progress
Week 1: Data Collection & Preprocessing

Created a simulated AQI dataset (30 days hourly)
Introduced and handled missing values
Applied feature engineering (Month, Day, Hour)
Visualized AQI trends and distributions
Exported cleaned dataset (processed_air_quality.csv) for Week 2

Week 2: Predictive Modeling

Split dataset into training and testing sets
Handled missing values using SimpleImputer
Trained two models:
Linear Regression (baseline)
Random Forest Regressor (better model)
Evaluated models using MAE, MSE, R² Score
Visualized actual vs predicted AQI
Saved the trained model (aqi_model.pkl)
Generated evaluation report (model_evaluation_report.txt)
____________________________________________________________________________________________________
Sample Evaluation Report
Model Evaluation Report - Week 2
================================
Linear Regression:
 MAE=15.62, MSE=420.48, R²=0.62

Random Forest:
 MAE=7.34, MSE=128.21, R²=0.89
____________________________________________________________________________________________________
Folder Structure
EcoAware-Project/
│── Week1/
│   ├── Week1_Data_Preprocessing.ipynb     # Data preprocessing notebook
│   ├── processed_air_quality.csv          # Cleaned dataset (output of Week 1)
│
│── Week2/
│   ├── Week2_AQI_Modeling.ipynb           # Model training and evaluation notebook
│   ├── aqi_model.pkl                      # Trained AQI prediction model
│   ├── model_evaluation_report.txt        # Evaluation metrics report
│
│── requirements.txt                       # Required Python libraries
│── README.md                              # Project documentation
____________________________________________________________________________________________________