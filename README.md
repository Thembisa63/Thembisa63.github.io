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
























