
# Day 1: Data Cleaning and Preprocessing

## Task Objective
The goal of this task is to clean and preprocess the Titanic dataset to prepare it for machine learning. This includes handling missing values, encoding categorical variables, scaling features, and removing outliers.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## Dataset
Titanic Dataset  
Source: https://www.kaggle.com/datasets/yasserh/titanic-dataset

## Steps Performed
1. Loaded the dataset and explored its structure
2. Handled missing values in 'Age' and 'Embarked'; dropped the 'Cabin' column
3. Encoded categorical variables: 'Sex' (label encoding), 'Embarked' (one-hot encoding)
4. Scaled 'Age' and 'Fare' using StandardScaler
5. Removed outliers in 'Age' and 'Fare' using the IQR method
6. Visualized the data using boxplots
7. Previewed the final cleaned dataset

## Files Included
- `task1_data_cleaning.ipynb` – Jupyter notebook containing the full preprocessing workflow
