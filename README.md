# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Titanic dataset** to uncover insights and patterns. The dataset contains information about Titanic passengers, such as their age, class, fare, and survival status.

## What is Done in the Code?

1. **Data Loading and Exploration**:
   - The Titanic dataset is loaded and the first few rows are displayed to understand its structure.

2. **Summary Statistics**:
   - Descriptive statistics (mean, median, etc.) for numerical columns are calculated to understand the data better.

3. **Missing Values Check**:
   - The code checks for missing data and visualizes it using a heatmap to see which columns have missing values.

4. **Univariate Analysis**:
   - Histograms and boxplots are created to understand the distribution of numerical features like age and fare.

5. **Bivariate Analysis**:
   - A correlation matrix and pairplot are used to explore relationships between numerical features.

6. **Categorical Feature Exploration**:
   - Count plots are created to visualize the distribution of categorical features like sex and passenger class.

7. **Interactive Visualizations**:
   - Plotly is used to create interactive plots, such as survival rates by passenger class and age distribution by survival status.

8. **Key Insights**:
   - Females had a higher survival rate than males.
   - Passengers in 1st class survived more than those in 2nd or 3rd class.
   - Missing values were mostly in the `Cabin` and `Age` columns.
   - Features like `Age` and `Fare` have outliers and skewness.

## Tools Used

- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For basic data visualization.
- **Seaborn**: For advanced data visualization.
- **Plotly**: For interactive data visualizations.

## Conclusion

This EDA helps us better understand the Titanic dataset, providing useful insights that can guide further analysis or machine learning models. The notebook includes various visualizations to explore both numerical and categorical data, identify missing values, and detect trends and anomalies in the dataset.
