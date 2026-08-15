# Laptop Price Prediction

An end-to-end machine learning project to predict laptop prices based on technical specifications and hardware components[cite: 1].

## Overview
This project implements a complete machine learning workflow covering data ingestion, exploratory data analysis (EDA), data cleaning, feature engineering, and model optimization[cite: 1].

## Key Results
* **Best Model:** Tuned Random Forest Regressor[cite: 1]
* **R² Score:** 0.8511
* **RMSE:** 240.51 €
* **Primary Price Drivers:** RAM (GB), CPU Frequency & Architecture, SSD Storage, and GPU Configuration

## Project Pipeline
1. **Data Ingestion & Cleaning:** Handled missing values, removed duplicates, and extracted structured storage metrics (SSD/HDD in GB) from raw hardware strings[cite: 1].
2. **Exploratory Data Analysis (EDA):** Univariate, bivariate, and multivariate analysis analyzing correlations across hardware features and price distributions[cite: 1].
3. **Preprocessing:** Pipeline integration using `StandardScaler` for continuous features and `OneHotEncoder` for categorical features[cite: 1].
4. **Model Training & Comparison:** Evaluated Linear Regression, Decision Tree, Random Forest, and Gradient Boosting models[cite: 1].
5. **Hyperparameter Tuning:** 5-Fold Grid Search Optimization over tree depth, split criteria, and estimator count[cite: 1].

## Tech Stack
* Python (pandas, numpy, scikit-learn, seaborn, matplotlib)
* Google Colab / Jupyter Notebook

## Getting Started
1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/laptop-price-prediction.git
