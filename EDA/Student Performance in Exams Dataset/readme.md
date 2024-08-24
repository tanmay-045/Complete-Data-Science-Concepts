## EDA with Student Performance Indicator Dataset

### Overview

This repository contains the Exploratory Data Analysis (EDA) of the Student Performance Indicator dataset. The primary objective of this analysis is to understand how various factors such as gender, ethnicity, parental education, lunch type, and test preparation course influence students' performance in exams.

### Dataset Description

The dataset consists of 8 columns and 1000 rows, capturing the following attributes:

1. **Gender**: Sex of the students (Male/Female).
2. **Race/Ethnicity**: Ethnicity of students (Group A, B, C, D, E).
3. **Parental Level of Education**: The highest level of education attained by the parents (e.g., Bachelor's degree, Master's degree, etc.).
4. **Lunch**: Type of lunch (Standard or Free/Reduced).
5. **Test Preparation Course**: Whether the student completed the test preparation course (Completed/Not Completed).
6. **Math Score**: Student's score in Mathematics.
7. **Reading Score**: Student's score in Reading.
8. **Writing Score**: Student's score in Writing.

## Steps Followed for EDA

1. **Problem Statement**:
   - Defined the objective to analyze how different variables impact students' performance.

2. **Data Collection**:
   - Collected data from [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977).
   - The dataset contains 1000 records with 8 features.

3. **Data Checks**:
   - Performed various checks including:
     - Missing values.
     - Duplicates.
     - Data types.
     - Number of unique values per column.
     - Statistical summary of the dataset.
     - Categories present in categorical columns.

4. **Feature Segregation**:
   - Separated numerical and categorical features for targeted analysis.

5. **Exploratory Data Analysis (EDA)**:
   - Conducted analysis to explore relationships between features and their impact on students' performance.
   - Visualized data distributions and correlations.

## Key Findings

1. **Gender Differences**:
   - Female students generally scored higher than male students when taken as average.

2. **Parental Education Influence**:
   - Students whose parents have higher education levels tend to score better across all subjects.

3. **Impact of Lunch Type**:
   - Students who had standard lunch generally performed better than those who had free/reduced lunch.

4. **Race/Ethnicity**:  
   - Student of group A and B tend to perform poorly in exam (Also distribution for group A and group B is left skewed).
