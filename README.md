# house-price-prediction-ml
# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict house prices using **Linear Regression** based on various features such as income, house age, number of rooms, and population.
The dataset was cleaned, analyzed, and processed before training the machine learning model.

---

## 📊 Dataset

* Dataset Name: USA Housing Dataset

* Features Used:

  * Avg. Area Income
  * Avg. Area House Age
  * Avg. Area Number of Rooms
  * Area Population

* Target Variable:

  * Price

---

## ⚙️ Steps Performed

### ✅ Data Cleaning

* Checked for null values
* Removed unnecessary columns (e.g., Address)

### ✅ Exploratory Data Analysis (EDA)

* Correlation matrix analysis
* Heatmap visualization using Seaborn

### ✅ Feature Selection

* Removed multicollinearity using **Variance Inflation Factor (VIF)**
* Selected important predictors

### ✅ Model Building

* Train-Test Split (80:20)
* Linear Regression model training

### ✅ Model Evaluation

* R² Score used for accuracy measurement
* Scatter plot used to compare actual vs predicted prices

---

## 📈 Model Performance

* Achieved **R² Score ≈ 0.91 (Excellent Performance)**

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels

---

## 🚀 Conclusion

The Linear Regression model successfully predicted house prices with high accuracy.
Feature selection and multicollinearity handling improved model performance significantly.

---

## 📌 Future Improvements

* Try other ML models (Decision Tree, Random Forest)
* Perform hyperparameter tuning
* Use cross-validation

---

## 📊 Model Accuracy

- R² Score: 0.91
- Model: Linear Regression

⭐ If you like this project, feel free to give it a star!
