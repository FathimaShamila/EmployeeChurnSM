## Overview

This project is a comprehensive analysis of employee attrition within an organization.The project aims to identify key factors driving employees to leave,build predictive models to forecast churn, and provide actionable insights to the Human Resources (HR) and management teams.

The project is based on real-world HR datasets and leverages advanced data analytics techniques taught in the Google Advanced Data Analytics Professional Certificate.

## Project Objectives

- Understand patterns and trends in employee attrition.
- Identify the most important features influencing employee churn
- Build predictive models to forecast which employees are likely to leave
- Provide actionable insights to help reduce turnover.

## Tools & Technologies

- **Programming Language**: Python
- **Libraries**: Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn, XGBoost
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning Models**: Logistic Regression, Random Forest, XGBoost
- **Development Environment**: Jupyter Notebook, VS Code


## Dataset

The dataset that we'll be using for this project contains 14,999 rows and 10 columns for the variables listed below.
Source:[Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv)

**Variables**                                        

- satisfaction_level : Employee-reported job satisfaction level [0–1]
- last_evaluation	: Score of employee's last performance review [0–1]
- number_project	: Number of projects employee contributes to
- average_monthly_hours	: Average number of hours employee worked per month
- time_spend_company : How long the employee has been with the company(years)
- Work_accident	: Whether or not the employee experienced an accident                               while at work
- left : Whether or not the employee left the company
- promotion_last_5years : Whether or not the employee was promoted in the last                              5 years
- Department : The employee's department
- salary : The employee's salary (U.S. dollars)

## Key Steps

1. **Data Exploration**: Load and inspect the dataset to understand its structure and identify any issues. Explore summary statistics and visualize distributions of key features.
1. **Data Cleaning**: Handle missing values,outliers and data types to prepare the data for analysis.Encode categorical variables.Normalize or scale numerical features as needed.
1. **Feature Engineering**: Create new features that capture patterns related to churn. Perform feature selection using correlation analysis and importance ranking.
1. **Model Building**: Train multiple machine learning models to predict employee attrition:
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier 
5. **Model Evaluation**: Evaluate models using accuracy,precision,recall,F1-score and ROC-AUC.Use confusion matrices and visualizations to interpret performance.
6. **Insights**: Highlight actionable insights for HR interventions.
7. **Reporting**: Summarize findings and recommendations in a dashboard or report. Provide visualizations to support decision-making. 

 




