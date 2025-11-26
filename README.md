# Cattle Price Prediction Model

## Overview
This project implements a machine learning-based model to predict cattle prices accurately using key features like species, breed, age, lactation details, and milk production. It applies data preprocessing, feature engineering, exploratory data analysis, and compares multiple regression models to identify the best-performing approach. The final model leverages Random Forest regression for robust and reliable price prediction.

## Features
- Data loading and preprocessing including one-hot encoding and scaling  
- Feature engineering (age calculation from birth year)  
- Exploratory data analysis with visualizations (distribution, box plots, scatter plots)  
- Model comparison: Linear Regression, Ridge, Lasso, Random Forest  
- Performance evaluation using R², RMSE, and MAE metrics  
- Feature importance visualization for interpretability  
- Predict price for new cattle samples  
- Model persistence with joblib for easy reuse  

## Installation and Usage
1. Clone this repository  
2. Install dependencies: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`  
3. Mount Google Drive (if using Colab) and place the dataset `animal.xlsx` in the specified folder  
4. Run the notebook/script to train models and generate predictions  

## Dataset
The dataset includes cattle attributes such as species, breed, gender, birth year, lactation details, milk production, and recorded prices. It is used to train and test the models effectively.

## Results
- The Random Forest model achieved an R² score above 0.95, indicating excellent predictive performance  
- RMSE and MAE values demonstrate low average deviation from actual prices  
- Feature importance analysis provides insights into key factors influencing cattle prices  

## Future Work
- Hyperparameter tuning and cross-validation for improved model robustness  
- Incorporation of additional features or external market data  
- Deployment as an API or web application for real-time price prediction  
