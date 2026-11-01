# House Price Prediction using Linear Regression

## Project Overview
This project focuses on predicting house prices using Machine Learning techniques. Linear Regression is used to estimate house prices based on important property features such as living area, house quality, garage capacity, location and number of bedrooms.

## Objective
To develop and evaluate a machine learning model that predicts house prices using historical housing data.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset
**Dataset:** Ames Housing Dataset

The dataset contains information about residential houses, including:
- Living area
- Overall quality
- Garage capacity
- Basement area
- Year built
- Neighborhood
- Number of bedrooms
- Sale price

## Project Workflow

1. Loaded and explored the housing dataset.
2. Checked missing values and duplicate records.
3. Performed exploratory data analysis (EDA).
4. Selected important features for prediction.
5. Handled missing values using imputation.
6. Applied One-Hot Encoding to categorical features.
7. Created a correlation heatmap.
8. Split the dataset into 80% training and 20% testing data.
9. Trained a Linear Regression model.
10. Evaluated the model using MSE, RMSE and R² score.
11. Created actual vs predicted and residual plots.
12. Analyzed model coefficients.
13. Implemented Ridge Regression for comparison.

## Machine Learning Models
- Linear Regression
- Ridge Regression

## Evaluation Metrics
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Measures how well the model explains variations in house prices.

## Project Structure

```text
DataAnalytics-Level2-Task1-HousePricePrediction/
│
├── train.csv
├── OIBSIP_Level2_Task1_House_Price_Prediction.ipynb
├── README.md
│
└── Outputs/
    ├── house_price_predictions.csv
    ├── model_comparison.csv
    └── model_coefficients.csv
```

## Conclusion
The project demonstrates how machine learning can be used to predict house prices based on property characteristics. Linear Regression was trained and evaluated, and Ridge Regression was implemented to compare model performance.

## Internship
Oasis Infobyte – Data Analytics Internship

**Project:** Level 2 – Task 1: House Price Prediction