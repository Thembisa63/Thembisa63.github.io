# Project 1


# Sports Data Analytics Project #

## Table of Contents 

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)


### Project Overview ###

The primary objective was to identify key factors that contribute to a striker's success and build a model to classify players based on their goal-scoring abilities and overall effectiveness on the field.


### Data Sources 

Strikers Performance: The primary dataset used for this analysis is the strikers_performance.xlsx containing detailed information about about each striker.

## Tools

- Python
- Pandas: Data manipulation and analysis.
- NumPy: Numerical computing and data handling.
- Matplotlib/Seaborn: Data visualization to uncover insights and patterns.
- Scikit-learn: Machine learning tools for building classification models.


## Data Cleaning

In the initial preparation place, I performed the following:

1.Data loading.
2.Handling missing values.
3.Assign the correct datatype for each column.
4.Check for duplicates.

## Data analysis 

```python

avg_goal_scored = round(data.groupby('Nationality')['Goals Scored'].mean(),2
avg_goal_scored

```

### Findings

Key performance metrics such as goals scored, assists significantly impact a striker's classification as the best.
Strikers with a higher conversion are more likely to be classified as best strikers.

### Recommendations

- Teams should focus on improving shot accuracy and key pass statistics to enhance striker performance.
- More focus should be given to strikers who can efficiently convert opportunities into goals.

# Project 2

## Exploratory Data Analysis On Retail Sales

### Project Overview 

This project focuses on performing an Exploratory Data Analysis (EDA) of retail sales data using Python. The primary objective was to analyze the dataset to uncover key insights about sales trends, customer behavior, and product performance, and to provide data-driven recommendations for improving retail operations.

### Data Sources

Retail sales dataset: The primary dataset used for this analysis is the retail_sales_dataset.csv containing detailed information about about the sales.

## Tools Used

- Programming Language: Python
- Development Environment: Jupyter Notebook
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn

## Data Cleaning

- Checking for duplicates
- Checking for missing values
- Checking for correct datatypes in each column


## Findings

Top Products: Certain products, like electronics consistently outperformed others in terms of revenue and volume.
Customer Behavior: High purchase rates among certain customer segments(those who earn more) were observed suggesting loyalty opportunities

### Recommendations 

- Focus marketing campaigns on peak sales periods to maximize revenue.
- Promote top-performing products like electronics and explore bundling strategies with complementary items.
- Implement a loyalty program to reward high-value customers and encourage repeat purchases.

# Project 3

# Customer Segmentation Analysis

#### Project Overview 

This project involves analyzing customer data to identify distinct customer groups using K-Means Clustering. The goal was to leverage segmentation insights to drive targeted marketing strategies and improve customer experience.

### Data Sources







### Tools Used

- Programming Language: Python
- Development Environment: Jupyter Notebook
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn


### Findings

Customer Groups: Identified distinct clusters, such as high-value customers, frequent shoppers, and low-engagement customers.
Spending Patterns: Certain clusters showed a higher average spend and transaction frequency, indicating strong profitability potential.

### Recommendations 

- Develop personalized marketing campaigns tailored to each customer segment.
- Offer exclusive promotions and rewards for high-value customers to enhance loyalty.




















