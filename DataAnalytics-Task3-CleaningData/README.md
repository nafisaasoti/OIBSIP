# Task 3: Cleaning Data

## Internship
Oasis Infobyte — Data Analytics Internship

## Objective
To transform a messy dataset into a clean, analysis-ready dataset by identifying and handling data quality issues.

## Dataset
Titanic passenger dataset.

## Tools Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Cleaning Steps
1. Inspected dataset dimensions, column names, data types, and summary statistics.
2. Created a data quality report covering missing values, duplicates, and unique values.
3. Filled missing Age values using the median.
4. Filled missing Embarked values using the mode.
5. Dropped Cabin because more than 50% of its values were missing.
6. Identified and removed exact duplicate rows.
7. Standardized text formatting and category capitalization.
8. Reviewed and corrected data types.
9. Detected potential numeric outliers using the IQR method.
10. Compared data quality before and after cleaning.
11. Exported the cleaned dataset to CSV.

## Project Files
- `OIBSIP_Task3_Cleaning_Data.ipynb` — Jupyter Notebook containing the cleaning process.
- `titanic_cleaned.csv` — Cleaned dataset.
- `README.md` — Project documentation.

## Conclusion
The project demonstrates a systematic approach to data cleaning and documentation. The cleaned dataset is prepared for further analysis, with potential outliers retained where they may represent valid observations.