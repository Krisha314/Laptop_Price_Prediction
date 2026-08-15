# Laptop Price Prediction

An end-to-end machine learning project to predict laptop prices based on technical specifications and hardware components.

## Overview
This project implements a complete machine learning workflow covering data ingestion, exploratory data analysis (EDA), data cleaning, feature engineering, and model optimization.

## Key Results
* **Best Model:** Tuned Random Forest Regressor.
* **R² Score:** 0.8511
* **RMSE:** 240.51 €
* **Primary Price Drivers:** RAM (GB), CPU Frequency & Architecture, SSD Storage, and GPU Configuration

## Project Pipeline
1. **Data Ingestion & Cleaning:** Handled missing values, removed duplicates, and extracted structured storage metrics (SSD/HDD in GB) from raw hardware strings.
2. **Exploratory Data Analysis (EDA):** Univariate, bivariate, and multivariate analysis analyzing correlations across hardware features and price distributions.
3. **Preprocessing:** Pipeline integration using `StandardScaler` for continuous features and `OneHotEncoder` for categorical features.
4. **Model Training & Comparison:** Evaluated Linear Regression, Decision Tree, Random Forest, and Gradient Boosting models.
5. **Hyperparameter Tuning:** 5-Fold Grid Search Optimization over tree depth, split criteria, and estimator count.

## Tech Stack
* Python (pandas, numpy, scikit-learn, seaborn, matplotlib)
* Google Colab / Jupyter Notebook

