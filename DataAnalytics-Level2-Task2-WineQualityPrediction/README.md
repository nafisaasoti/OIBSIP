# OIBSIP Level 2 – Task 2
# Wine Quality Prediction

## Project Overview
This project uses Machine Learning classification algorithms to predict wine quality based on its physicochemical properties.

The project uses Red Wine and White Wine datasets and classifies wine into three categories: Low, Medium and High.

## Objective
To build and compare different machine learning models for predicting wine quality.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
The project uses the Wine Quality dataset from the UCI Machine Learning Repository.

It contains:
- Red Wine Dataset
- White Wine Dataset

The dataset includes chemical properties such as alcohol, acidity, pH, density and sulphates.

## Machine Learning Algorithms
Three classification algorithms are implemented:

1. Random Forest Classifier
2. SGD Classifier
3. Support Vector Classifier (SVC)

## Project Workflow
1. Load and inspect the datasets.
2. Combine red and white wine data.
3. Perform data cleaning and exploratory data analysis.
4. Visualize wine quality distribution.
5. Convert quality scores into Low, Medium and High categories.
6. Encode categorical features.
7. Split data using stratified sampling.
8. Apply feature scaling.
9. Train three classification models.
10. Evaluate and compare model performance.
11. Analyze feature importance.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Project Structure

```text
DataAnalytics-Level2-Task2-WineQualityPrediction/
│
├── OIBSIP_Level2_Task2_Wine_Quality_Prediction.ipynb
├── wine+quality (1)/
│   ├── winequality-red.csv
│   └── winequality-white.csv
│
├── Outputs/
│   ├── model_comparison.csv
│   ├── feature_importance.csv
│   └── wine_quality_predictions.csv
│
├── Screenshots/
│
└── README.md
```

## Conclusion
This project demonstrates how machine learning algorithms can predict wine quality using chemical properties. The performance of Random Forest, SGD and SVC models is compared to identify the best-performing model on the test dataset.
