# Analysis of Student Performance Factors: What Drives Student Success

**OMIS 630 – Python Programming for Business**  
**Academic Project | Group 5**

**Contributors:** Akshata Pai

## Project Overview

This project examines the academic, behavioral, and socioeconomic factors associated with student performance using Python, exploratory data analysis, statistical modeling, and machine learning.

The analysis focuses on understanding student exam performance, identifying important influencing factors, and exploring how students can be segmented based on academic and behavioral characteristics.

## Dataset

**Source:** Kaggle – Student Performance Factors Dataset

The dataset contains **6,607 observations and 20 variables** and is synthetic, created for educational and analytical purposes.

The variables cover three main categories:

- **Academic factors:** Hours studied, attendance, previous scores, tutoring sessions, and exam scores.
- **Lifestyle factors:** Sleep hours, physical activity, and extracurricular activities.
- **Environmental and socioeconomic factors:** Parental involvement, family income, access to resources, internet access, and school type.

Missing values in selected categorical variables were handled using mode imputation.

## Project Objectives

1. Explore the relationships between student characteristics and exam performance.
2. Develop a multiple regression model to examine factors associated with exam scores.
3. Segment students using K-Means clustering.
4. Apply Decision Tree classification to investigate the identification of at-risk students.
5. Develop recommendations for supporting academic success.

## Tools and Technologies

- **Python:** Programming and analysis
- **Pandas and NumPy:** Data manipulation and preprocessing
- **Matplotlib and Seaborn:** Data visualization
- **Statsmodels:** Multiple linear regression
- **Scikit-learn:** K-Means clustering and Decision Tree classification
- **Google Colab:** Notebook development

## Methodology and Findings

### 1. Exploratory Data Analysis

Exploratory analysis examined student performance distributions, study behavior, attendance, sleep duration, parental involvement, and other relevant characteristics.

The analysis highlighted relationships between academic performance and factors such as study hours, attendance, and parental involvement.

### 2. Multiple Linear Regression

An Ordinary Least Squares (OLS) regression model was developed to examine the relationship between exam scores and academic, behavioral, and contextual factors.

Sleep Hours was excluded from the final model after being identified as statistically insignificant.

**Findings reported in the academic report:**

- Approximately 67.4% of variation in exam scores was explained by the model.
- Study hours, attendance, tutoring sessions, and previous academic performance were significant predictors.
- Parental involvement, motivation, and access to educational resources were also associated with exam performance.
- Predictor VIF values were below 3, indicating low multicollinearity.

### 3. K-Means Clustering

K-Means clustering was applied to segment students based on:

- Exam Score
- Performance Change (Delta)
- Hours Studied
- Attendance

The Elbow Method was used to select **three clusters**.

The original academic report describes the following student segments:

- **At Risk:** Students with weaker performance trends requiring
