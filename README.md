# Social Media User Engagement Analysis using Decision Tree

## 📋 Project Description

This project aims to predict **User Engagement Score** on social media platforms using machine learning models. The main focus is on tree-based models, particularly **Decision Tree Regressor** and **Random Forest Regressor**, along with experiments using Linear Regression.

The analysis includes data exploration, handling categorical variables, outlier treatment, feature encoding, and model evaluation.

## 🛠️ Technologies & Libraries

- **pandas** & **numpy**
- **scikit-learn** (LinearRegression, DecisionTreeRegressor, RandomForestRegressor)
- **seaborn** & **matplotlib**

## 📁 Files

- `decision_tree_jermy.ipynb` → Main Jupyter Notebook
- because data it to large hete is the url social_media Dataset: https://www.kaggle.com/datasets/rockyt07/social-media-user-analysis

## 🚀 How to Run
1. Install required libraries:Bash
pip install pandas numpy scikit-learn seaborn matplotlib
2.Launch the notebook:Bash
jupyter notebook decision_tree_jermy.ipynb
Main Steps

Data loading and exploration (EDA)
Categorical variables processing and ordering (Income, Education, Privacy, Subscription)
Custom encoding with train_cats() and proc_df()
Correlation analysis (Spearman)
Outlier handling
Building models:
Simple & Multiple Linear Regression
Decision Tree Regressor
Random Forest Regressor

Model evaluation using R², MSE, and RMSE on train and validation sets

🔍 Key Findings

Random Forest performed better than single Decision Tree
Significant overfitting observed with deep Decision Trees (max_depth=58)
Log transformation was applied on the target variable for better distribution
Feature importance and correlation patterns were explored
