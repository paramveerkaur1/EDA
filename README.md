#  Titanic Dataset Exploratory Data Analysis (EDA)
This project performs exploratory data analysis (EDA) on the Titanic dataset using Python libraries like Pandas, Matplotlib, Seaborn etc.

 # Objectives
This EDA aims to:
- Generate summary statistics for understanding the distribution of the data.
- Visualize numeric features using histograms and boxplots.
- Analyze relationships between features using pairplots and a correlation matrix.
- Identify meaningful patterns, trends, and anomalies.
- Draw basic feature-level inferences based on visuals.

# Tools & Libraries
Python, Pandas, Seaborn, Matplotlib

# Steps

1. Generate Summary Statistics
- Use .describe() to generate descriptive statistics such as: Mean, Median(50% Quartile), Standard deviation, Minimum and maximum etc.

2. Create Histograms and Boxplots for Numeric Features
- Histograms visualize distribution and skewness of numeric data.
- Boxplots reveal central tendency, spread, and outliers.
  
3. Use Pairplot and Correlation Matrix
- Pairplot shows pairwise relationships between numeric variables.
- Correlation matrix (with heatmap) quantifies linear relationships.

4. Identify Patterns, Trends, and Anomalies
a. Age by Class: Survival Analysis Scatter plot is useful for following inferences:
- Class 1 has more yellow data points, hence more Class 1 travellers survives
- For Class 2 and 3, lower ages had comparitively higher survivals than higher ages
- Class 3 has least number of survivals
b. Fare by Gender Distribution Bar Chart helps to infer that:
- Females had to pay higher fare than males.

5️. Make Basic Feature-Level Inferences
Correlation Matrix helps to make following inferences about the numerical features:
- Fare and Survived have a positive correlation: Higher the fare, better the chances of survival
- Pclass and Survived have a negative correlation: Class 1 has higher survival chance than Class 3
- Age and Survived have a low negative correlation: Lower Age has slightly higher survival chance than Higher Age

# Conclusion
This EDA forms the foundation for understanding the Titanic dataset. The findings are essential for further data analysis in future.
