# Titanic Data Analysis

🔍 **Task Overview:**
The primary objective was to clean the dataset, handle missing values, drop irrelevant columns, and perform EDA to uncover insights. Here's a detailed breakdown of the technical steps taken:

## 🧹 Data Cleaning:

### Handling Missing Values:
- Filled missing values in the 'Age' column with the median age to maintain consistency.
- Filled missing values in the 'Embarked' column with the mode (most frequent value) to ensure no missing categorical data.
- Dropped the 'Cabin' column due to a high percentage of missing values (~77%).

### Dropping Irrelevant Columns:
- Removed 'Name' and 'Ticket' columns as they are not directly useful for analysis.

### Converting Categorical to Numerical:
- Converted 'Sex' to binary values: 0 for male and 1 for female.
- Converted 'Embarked' to numerical values: 0 for Cherbourg, 1 for Queenstown, and 2 for Southampton.

## 📊 Exploratory Data Analysis (EDA):

### Survival Distribution:
- Visualized the survival count using seaborn's countplot to understand the overall survival rate.

### Gender Distribution and Survival Rate:
- Analyzed the distribution of genders and their survival rates, revealing that women had a significantly higher survival rate.

### Pclass and Survival Rate:
- Investigated the relationship between passenger class and survival rates, showing higher survival rates for first-class passengers.

### Correlation Heatmap:
- Created a heatmap to visualize correlations between variables, helping to identify significant relationships.

## 📈 Relationship Analysis:

### Age and Survival:
- Boxplot analysis of age distribution by survival status to see how age influenced survival.

### Fare and Survival:
- Boxplot analysis of fare distribution by survival status, revealing that higher fares were associated with higher survival rates.

## ✨ Insights:

- **Survival Rate:** More passengers did not survive than those who did.
- **Gender and Survival:** Women had a higher survival rate compared to men.
- **Age Distribution:** Majority of passengers were aged between 20 and 40.
- **Class and Survival:** First-class passengers had a significantly higher survival rate.
- **Correlation:** Significant correlations found between survival and fare, class, and gender.

## Key Visualizations:

### Survival Count:
- A bar chart showing the overall count of survivors vs non-survivors.

### Gender and Survival Rate:
- A bar chart displaying the distribution of genders and their respective survival rates.

### Passenger Class and Survival Rate:
- A bar chart illustrating the survival rates across different passenger classes.

### Correlation Heatmap:
- A heatmap depicting the correlations between various features and survival.

### Age and Survival:
- A boxplot showing the age distribution of passengers based on their survival status.

### Fare and Survival:
- A boxplot displaying the fare distribution based on survival stat
