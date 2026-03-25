# House Prices Prediction - Advanced Regression

**Predicting residential house sale prices in Ames, Iowa** using Machine Learning, Feature Engineering and Ensemble Models (Kaggle Competition).

![Kaggle](https://img.shields.io/badge/Kaggle-Competition-blue)
![Python](https://img.shields.io/badge/Python-3.10+-yellow)
![XGBoost](https://img.shields.io/badge/XGBoost-Used-orange)

##  Problem Statement
The goal of this project is to predict the final sale price of residential homes in Ames, Iowa based on 79 explanatory variables (numerical and categorical features).

##  Dataset
- **Competition**: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- Training samples: 1460
- Test samples: 1459
- Features: 79 (numerical + categorical)

##  Technologies Used
- **Python** 3.10+
- Pandas, NumPy
- Scikit-learn, XGBoost, LightGBM
- Matplotlib, Seaborn
- Feature Engineering & Cross-Validation

## Project Workflow
1. **Exploratory Data Analysis (EDA)**
   - Analyzed target variable distribution → applied log transformation
   - Missing values analysis & visualization
   - Correlation heatmap
   - Outlier detection

2. **Data Cleaning & Preprocessing**
   - Handled missing values (numerical & categorical)
   - Removed low-variance and highly correlated features
   - Encoded categorical variables (One-Hot Encoding + Label Encoding)

3. **Feature Engineering**
   - Created new meaningful features (Total Area, Total Bathrooms, House Age, etc.)
   - Handled skewness in numerical features
   - Feature selection using correlation and importance scores

4. **Modeling**
   - Baseline models (Linear Regression, Random Forest)
   - Advanced models (XGBoost, LightGBM)
   - Hyperparameter tuning with GridSearchCV / Optuna
   - Ensemble & Stacking methods

5. **Evaluation**
   - Primary Metric: **Root Mean Squared Logarithmic Error (RMSLE)**
   - RMSE: 0.1246
   - **RMSLE**: 0.00888
   - R² Score: 0.8852
   - **Kaggle Public Score**: [ضع Score الـ Leaderboard هنا]

##  How to Run the Project
```bash
git clone https://github.com/mahmoud3t/house_prices_prediction_advanced_regression.git
cd house_prices_prediction_advanced_regression
pip install -r requirements.txt
jupyter notebook notebooks/

## --
Made by Mahmoud Shaker  
Self-taught Machine Learning & AI  
