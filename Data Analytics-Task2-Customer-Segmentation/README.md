# Task 2: Customer Segmentation Analysis using K-Means

## Internship
Oasis Infobyte — Data Analytics Internship

## Objective
To segment customers into different groups based on their purchasing behavior using the K-Means clustering algorithm. This analysis helps identify customer groups that can support better marketing strategies and business decisions.

## Dataset
**Online Retail Dataset**

The dataset contains online retail transaction records, including invoice details, product information, quantities, prices, and customer IDs.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Loaded and inspected the Online Retail dataset.
2. Explored the dataset to understand its structure and purchasing information.
3. Cleaned the data by handling missing values and removing invalid transaction records.
4. Calculated the total purchase amount for each transaction.
5. Created customer-level Recency, Frequency, and Monetary (RFM) features.
6. Applied log transformation to Frequency and Monetary values to reduce skewness.
7. Standardized the customer features using StandardScaler.
8. Used the Elbow Method to help select the number of clusters.
9. Applied the K-Means clustering algorithm to group customers.
10. Analyzed and compared the characteristics of the resulting customer segments.
11. Created visualizations to understand customer groups.
12. Exported the customer segmentation results to a CSV file.

## RFM Analysis

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How often a customer made purchases.
- **Monetary:** The total amount spent by a customer.

## Algorithm Used

**K-Means Clustering**

K-Means is an unsupervised machine learning algorithm that groups similar data points into clusters based on their feature values.

## Project Files

- `OIBSIP_Task2_Customer_Segmentation.ipynb` — Jupyter Notebook containing the analysis and implementation.
- `Online Retail.xlsx` — Original dataset.
- `customer_segmentation_results.csv` — Customer segmentation results.
- `README.md` — Project documentation.

## Conclusion

Customer segmentation was performed using the K-Means clustering algorithm and RFM-based customer features. The analysis grouped customers according to their purchasing behavior and provided visualizations to compare the resulting segments.

The project demonstrates how data analysis and unsupervised machine learning can help businesses understand customer behavior and support data-driven marketing decisions.
