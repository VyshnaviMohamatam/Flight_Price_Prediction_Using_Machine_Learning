# ✈️ Flight Price Prediction using Machine Learning

This project focuses on building a regression model to predict flight ticket prices based on various features such as airline, source, destination, duration, and stops. It uses real-world data and applies machine learning techniques with hyperparameter tuning for better prediction accuracy.

---

## 📌 Problem Statement

Given the flight details, the objective is to predict the price of flight tickets to help customers make better purchase decisions and airlines optimize their pricing strategy.

---

## 🔧 Tools & Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn** – for visualization
- **Scikit-learn** – for ML modeling
- **Optuna** – for hyperparameter tuning

---

## 📊 Dataset Overview

- Features used:
  - Airline
  - Source & Destination
  - Total Stops
  - Journey Day & Month
  - Duration
  - Arrival/Departure Time
  
You can find sample data in the `data/` folder (Note: actual dataset might be large, so use a sample if uploading).

---

## 🧠 Machine Learning Approach

1. **Data Preprocessing**
   - Missing value handling
   - Feature engineering (Duration, Day/Month of Journey)
   - Categorical encoding (Label/One-Hot)
   - Outlier removal

2. **Modeling**
   - Algorithms tried:
     - Decision Tree Regressor
     - Random Forest Regressor ✅
   - Used `Optuna` for hyperparameter tuning

3. **Evaluation Metrics**
   - R² Score

---
---

## 🚀 How to Run This Project

1. Clone the repository:
https://huggingface.co/spaces/MohamatmVyshnavi/Flight_Price_Prediction
