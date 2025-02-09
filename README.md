# Autism Spectrum Disorder (ASD) Screening Data Analysis #

This project performs data cleaning, preprocessing, and exploratory data analysis (EDA) on an ASD screening dataset. It involves:

1. Data Cleaning – Handling missing values, formatting data, and standardizing categorical variables.
2. Exploratory Data Analysis (EDA) – Visualizing feature distributions, class imbalance, and categorical variable trends.
3. Outlier Detection – Identifying outliers using statistical methods (IQR).
4. Insights for Machine Learning – Understanding patterns in ASD screening data to support predictive modeling.

# Program Breakdown
1. Data Loading & Exploration: 
Reads the dataset (train.csv) using pandas.
Displays basic details such as column names, data types, and missing values.
Checks for unique values in categorical columns.
2. Data Cleaning & Transformation:
Converts the age column from string to integer.
Drops unnecessary columns:
ID (irrelevant unique identifier).
age_desc (contains redundant information).
Standardizes country names to avoid inconsistencies.
3. Exploratory Data Analysis (EDA)
Analyzes the distribution of the target variable (Class/ASD).
Checks for class imbalance (significant difference in ASD-positive vs. negative cases).
Plots histograms & boxplots to visualize distributions of numerical features (age, result).
4. Outlier Detection & Handling
Uses the Interquartile Range (IQR) method to detect outliers in numerical columns.
Counts and visualizes the outliers.
5. Categorical Data Analysis
Plots count distributions of categorical variables (e.g., gender, ethnicity, country of residence).
Identifies potential correlations between categorical features and ASD diagnosis.
