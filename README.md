# Flight Price Prediction

## Project Overview

This project focuses on predicting flight ticket prices using machine learning regression techniques.

The project includes data cleaning, feature engineering, exploratory data analysis, preprocessing, model development, model comparison, prediction analysis, and residual analysis.

## Dataset

The dataset contains flight-related information such as:

- Airline
- Source
- Destination
- Route
- Journey Date
- Departure Time
- Arrival Time
- Duration
- Total Stops
- Additional Information
- Flight Price

## Data Preprocessing

The following preprocessing steps were performed:

- Missing value handling
- Duplicate removal
- Date and time feature extraction
- Flight duration conversion into minutes
- Total stops conversion into numerical format
- Categorical feature encoding using One-Hot Encoding
- Numerical feature scaling using StandardScaler

## Exploratory Data Analysis

The project analyzes relationships between flight prices and different features including:

- Journey month
- Departure hour
- Arrival hour
- Flight duration
- Number of stops

Correlation analysis was also performed on numerical features.

## Machine Learning Models

Four regression models were trained and evaluated:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Random Forest | 620.77 | 1424.40 | 0.9027 |
| Decision Tree | 762.01 | 1904.63 | 0.8260 |
| Gradient Boosting | 1267.83 | 1991.26 | 0.8098 |
| Linear Regression | 1544.71 | 2436.38 | 0.7153 |

Random Forest Regressor was selected as the final candidate model based on its test-set performance.

## Final Model Analysis

The selected model was evaluated using:

- Actual vs Predicted Flight Prices
- Prediction Residuals
- Residual Distribution
- Residuals vs Predicted Prices

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
flight-price-prediction/
│
├── Flight_Price_Prediction.ipynb
└── README.md
