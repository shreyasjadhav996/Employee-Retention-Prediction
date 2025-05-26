# Predicting Employee Retention

## Problem Statement
Employee retention is critical for organizations, impacting productivity, morale, and financial performance. Predicting employee retention can help organizations proactively address factors leading to attrition and implement strategies to retain valuable employees.

## Objective
The objective of this project is to develop a Logistic Regression model to predict employee retention based on various factors such as demographic details, job satisfaction scores, performance metrics, and tenure. The goal is to provide actionable insights to the HR department to strengthen retention strategies and create a supportive work environment.

## Dataset Overview
The dataset contains 24 columns and 74,610 rows, with features including:
- **Employee ID**: Unique identifier for each employee.
- **Age**: Employee age (18-60 years).
- **Gender**: Employee gender.
- **Years at Company**: Duration of employment.
- **Monthly Income**: Monthly salary in dollars.
- **Job Role**: Department or role (e.g., Finance, Healthcare, Technology).
- **Work-Life Balance**: Employee perception (Poor, Below Average, Good, Excellent).
- **Job Satisfaction**: Satisfaction level (Very Low, Low, Medium, High).
- **Performance Rating**: Employee performance (Low, Below Average, Average, High).
- **Attrition**: Whether the employee has left the company (Stayed/Left).

## Project Steps
1. **Data Understanding**: Load and explore the dataset to understand its structure and features.
2. **Data Cleaning**: Handle missing values, redundant columns, and categorical data.
3. **Train-Validation Split**: Split the data into training (70%) and validation (30%) sets.
4. **Exploratory Data Analysis (EDA)**: Analyze training data to uncover patterns and insights.
5. **Feature Engineering**: Create or transform features to improve model performance.
6. **Model Building**: Develop a Logistic Regression model.
7. **Prediction and Evaluation**: Assess model performance using validation data.

