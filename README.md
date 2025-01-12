# Student Dataset Cleaning and analysis

### Project Overview

This project focuses on cleaning and exploring a dataset using Python to uncover insights and answer specific questions. The process includes handling missing data, fixing inconsistencies, and using visualizations to identify patterns and trends. The goal is to draw simple, actionable conclusions from the data.

### Data

The dataset contains student information, including demographics, academic background, and personal attributes. Key features include Age, Height, Weight, Credit Amount, Marital Status, car ownership, and favorite apps.

### Tool

Python

### Data Cleaning

- Data cleaning prepared the dataset for analysis by addressing missing values, data types, and formats.  
- Missing values were replaced, using the mode for categorical data.  
- Inconsistent formats, like heights, were standardized to centimeters.  
- The `personal_status` column was split into `Gender` and `Marital Status`.  
- Data types were corrected, and anomalies were resolved for accuracy.

### EDA

- Summary statistics were calculated for numeric columns.  
- The count of males and females was determined using the `Gender` column.  
- Mean 'Credit Amount' was calculated by grouping data by `Gender`.  
- Average credit amount by 'Car Company' type was computed and sorted in descending order.  
- The range for the 'Age' column was calculated.

### Visualization

- Q1: Does age correlate with credit amount, and if so, how?
- Q2: Identify the top 10 female students with the highest weights (lbs).  
- Q3: What is the average weight across different age groups? 
- Q4: How does marital status relate to credit amount?
- Q5: What is the distribution of student ages?

### Findings

- Age has a weak positive correlation with credit amount, suggesting a minimal impact.  
- Singles have higher credit amounts, with several outliers reaching over 15,000.  
- Divorced/separated and widowed individuals generally have lower credit amounts.  
- 46–70 age group shows the highest average weight, indicating a potential trend in weight distribution.  
- Most students are between 21 and 40 years old, with a peak at age 33.

### Recommendations

- Target singles: Focus on products for those with higher credit amounts.  
- Age-based services: Tailor wellness programs for the 46–70 age group.  
- Address credit outliers: Provide personalized support for outlier groups.  
- Focus on 21–40 age group: This group makes up the majority of students.  
- Explore age and credit: Further analysis may reveal insights for specific subgroups.

### References

"Python for Data Analysis" by Wes McKinney
[Stack overflow](https://stack.com)

