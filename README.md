# 🌬️ AeroVita – AI-Powered Air Quality & Health Risk Prediction System
AeroVita is an AI-driven environmental health intelligence system that predicts:<br>
● IndianA QI <br>
● Asthma Risk (Low / Medium / High)<br>
● Breathability Score (0–100) <br>
● Outdoor Safety (Safe / Unsafe) <br>
● Live AQI using WAQI API <br>
Built using machine learning, environmental science, and medical scoring rules, AeroVita transforms raw pollutant data into real-time health insights.

## 🚀 Features
### ⭐ 1. Indian AQI Prediction (NAQI Standard)

Predicts AQI based on Indian CPCB breakpoints using <br>
PM2.5, PM10, NO₂, SO₂, CO, O₃.

### ⭐ 2. Respiratory Health Predictions

● Asthma Attack Risk <br>
● Breathability Index <br>
● Outdoor Safety Recommendation

### ⭐ 3. Medical Scoring Engine

A clinical-style scoring system combining: <br>
● particulate concentration <br>
● temperature<br>
● humidity <br>
● NO₂ respiratory irritation <br>
● environmental stressors <br>

Generates:
● Medical Score (0–10) <br>
● Medical Risk Label <br>

### ⭐ 4. Real-Time AQI via WAQI API

Fetches: <br>
● Live pollutant concentrations <br>
● Live AQI (US EPA AQI) <br>
● Weather conditions<br>

Processes them through your custom Indian AQI model and health models.

### ⭐ 5. Visualizations

● Asthma trend plots <br>
● Medical score distribution <br>
● AQI relationships (PM2.5 vs AQI)<br>
● Model accuracy heatmaps <br>
● Breathability vs AQI <br>
● Regression/Classification metrics <br>

## 📊 Tech Stack

### Machine Learning
● Random Forest Classifier <br>
● Random Forest Regressor <br>
● Train/Test split <br>
● Evaluation: Accuracy, F1-score, MAE, RMSE, R² <br>
● Python Libraries <br>
● pandas <br>
● numpy <br>
● matplotlib <br>
● seaborn <br>
● scikit-learn <br>
● requests <br>

### APIs
● WAQI API (live AQI) <br>
● Development <br>
● Google Colab
