# Day 2: Exploratory Data Analysis (EDA)

## Objective

The goal of this task is to perform exploratory data analysis (EDA) on the Titanic dataset to better understand the structure, patterns, and relationships within the data. This includes generating summary statistics, creating visualizations, and identifying meaningful insights that will help in future machine learning tasks.

## Tools and Libraries

- Python
- Pandas
- Seaborn
- Matplotlib

## Steps Performed

1. Loaded the Titanic dataset and explored its structure
2. Checked for missing values and basic descriptive statistics
3. Created histograms and boxplots for numeric features like Age and Fare
4. Plotted countplots for categorical features such as Sex, Pclass, and Embarked
5. Created a correlation matrix to understand relationships between numerical variables
6. Used pairplots to explore interactions between survival and key features

## Visualizations Included

- Histograms of `Age` and `Fare`
- Boxplots to detect outliers in `Age` and `Fare`
- Countplots for `Sex`, `Pclass`, `Embarked`, and `Survived`
- Correlation heatmap for numerical features
- Pairplot showing interaction between `Survived`, `Age`, `Fare`, and `Pclass`
- Bar plot of survival rate by gender

## Final Observations from Visualizations

- **Survival Rate by Gender**: Females had a significantly higher survival rate (~74%) compared to males (~19%).
- **Survival Rate by Passenger Class (Pclass)**: First class passengers had the highest survival rate, third class had the lowest.
- **Age Distribution**: Most passengers were aged 20–40. Children had slightly better survival chances.
- **Fare Distribution**: Most passengers paid fares below 50. Higher fares were linked to higher survival probability.
- **Embarkation Port**: Majority of passengers boarded at 'S'. Those who embarked at 'C' had slightly better survival outcomes.
- **Correlation Matrix**: Showed strong correlation between survival and features like `Sex`, `Pclass`, and `Fare`.

