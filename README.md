 – Activity 1: Dataset Preparation

## Project Overview
This project is completed as part of the Machine Learning CIE 2 Activity 1 – Dataset Preparation.

The objective is to inspect a dataset, identify data-quality issues, handle missing values, perform Exploratory Data Analysis (EDA), encode categorical variables, scale numerical features, and prepare a cleaned dataset for future machine learning applications.

## Dataset Information
- **Dataset Name:** Titanic Dataset
- **Domain:** Transport
- **File Format:** CSV
- **Original Rows:** 891
- **Original Columns:** 15
- **Target Column:** survived

### Dataset Source
https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv

## Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Activities Performed
1. Dataset selection and loading.
2. Dataset inspection and understanding.
3. Numerical and categorical feature identification.
4. Missing-value analysis and treatment.
5. Duplicate checking and data consistency.
6. Exploratory Data Analysis (EDA).
7. Data visualization using histograms, bar charts, and box plots.
8. Categorical feature encoding using One-Hot Encoding.
9. Numerical feature scaling using StandardScaler.
10. Saving the final prepared dataset as a CSV file.

## Data Cleaning
- Age: Missing values replaced using median.
- Embarked: Missing values replaced using mode.
- Deck: Removed because of excessive missing values.
- Redundant columns: Removed.
- Duplicate records: Checked and unwanted exact duplicates removed.
- Categorical values: Standardized.

## Final Output
- Activity_1_Dataset_Preparation.ipynb
- Titanic_Prepared_Dataset.csv

## Conclusion
The Titanic dataset was inspected, cleaned, analyzed, encoded, and scaled. The prepared dataset is available for further machine learning experimentation.

## Faculty Profile and Acknowledgement

Faculty Profile: https://github.com/Princy2129

This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: https://github.com/Princy2129

