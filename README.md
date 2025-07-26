# 🏡 Prediction of House Prices with Extreme Gradient Boosting

This repository contains the complete implementation of my Final Year Project (FYP) titled **"Prediction of House Prices with Extreme Gradient Boosting"**, which aims to build a reliable machine learning model to predict residential house prices based on various property features. The system uses real-world housing data and leverages advanced tree-based ensemble methods to deliver accurate and interpretable results.

## 📌 Project Overview

House price prediction is an essential tool in the real estate industry for assisting buyers, sellers, investors, and policymakers. This project focuses on using the **Extreme Gradient Boosting (XGBoost)** algorithm to model the complex relationships between property features and their corresponding prices.

The final model achieves a strong performance with an **R² score of 0.9117**, demonstrating its effectiveness in regression tasks involving real-world housing datasets.

---

## 🧠 Technologies Used

- Python 3.x  
- XGBoost  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Flask (for web deployment)  
- HTML, CSS (frontend)

---

## 🗃️ Dataset

The dataset used in this project is a cleaned and preprocessed version of a real-world housing dataset. It includes features such as:

- Overall Quality
- Living Area (GrLivArea)
- Total Basement Area
- Garage Area
- Year Built
- Number of Bathrooms
- Lot Area
- Neighborhood
- ...and many more

---

## 📈 Model Development Workflow

1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Outlier removal
   - Feature encoding
   - Feature scaling

2. **Model Building**
   - Baseline model: Linear Regression
   - Advanced models: Decision Tree, Random Forest, Gradient Boosting, XGBoost

3. **Model Evaluation**
   - Metrics: MAE, MSE, RMSE, R²
   - Visualizations: Actual vs Predicted plots, Residual plots, Feature importance

4. **Hyperparameter Tuning**
   - GridSearchCV to optimize XGBoost parameters

5. **Deployment**
   - Flask-based web application
   - User inputs property details → system returns predicted price

---

## 🧪 Results

- **Best Model**: XGBoost Regressor  
- **R² Score**: 0.9117  
- **Prediction Dashboard**: Deployed locally via Flask with HTML frontend

---

## 🌐 Web Application Preview

<p align="center">
  <img src="static/demo-screenshot.png" alt="Web App Screenshot" width="600">
</p>

The web app allows users to enter property details and get a real-time price prediction powered by the trained XGBoost model.

---

