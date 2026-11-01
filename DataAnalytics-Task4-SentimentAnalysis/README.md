# Task 4: Sentiment Analysis

## Internship
Oasis Infobyte — Data Analytics Internship

## Objective
To analyze text data and classify tweets into sentiment categories using Natural Language Processing (NLP) and machine learning.

## Dataset
Twitter Entity Sentiment Analysis dataset.

The dataset contains tweet text and sentiment labels, including Positive, Negative, Neutral, and Irrelevant.

## Tools and Libraries
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- WordCloud
- Jupyter Notebook

## Project Workflow
1. Loaded and explored the training and validation datasets.
2. Examined sentiment distribution and data quality.
3. Removed missing and duplicate records where applicable.
4. Preprocessed tweet text by converting it to lowercase and removing URLs, mentions, punctuation, and unnecessary characters.
5. Used TF-IDF to convert text into numerical features.
6. Trained Logistic Regression and Multinomial Naive Bayes classifiers.
7. Evaluated both models using accuracy, precision, recall, F1-score, and confusion matrices.
8. Visualized sentiment distributions and generated word clouds.
9. Examined five misclassified tweets.
10. Saved model comparison metrics and sentiment predictions as CSV files.

## Output Files
- `OIBSIP_Task4_Sentiment_Analysis.ipynb` — Project notebook.
- `sentiment_model_comparison.csv` — Model evaluation results.
- `sentiment_predictions.csv` — Actual and predicted sentiment labels.

## Conclusion
This project demonstrates how NLP and machine learning can be used to analyze social media opinions. Such techniques can support customer feedback analysis, product review monitoring, and social media sentiment tracking. Predictions may be affected by sarcasm, slang, and context.

## Note
The notebook uses separate training and validation files. The evaluation procedure should be documented according to the internship requirements.