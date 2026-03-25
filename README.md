# House Price Prediction

This is my solution for the Kaggle competition "House Prices - Advanced Regression Techniques".

I developed a machine learning model to predict the final sale price of houses in Ames, Iowa based on 79 features.

## Project Overview
- Performed Exploratory Data Analysis (EDA)
- Cleaned the dataset and handled missing values
- Applied feature engineering (created new features such as total area, house age, total bathrooms, etc.)
- Trained and compared several models (Linear Regression, Random Forest, XGBoost, LightGBM)
- Used hyperparameter tuning and ensemble techniques to improve performance
- Applied log transformation to the target variable due to skewness

## Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost, LightGBM
- Matplotlib, Seaborn

## Results
- RMSLE: 0.00888
- RMSE: 0.1246
- R² Score: 0.8852

## How to Run
```bash
git clone https://github.com/mahmoud3t/house_prices_prediction_advanced_regression.git
cd house_prices_prediction_advanced_regression
pip install -r requirements.txt
jupyter notebook notebooks/


##
Made by Mahmoud Shaker  
Aspiring Fachinformatiker für Anwendungsentwicklung  
Self-taught Machine Learning & AI
