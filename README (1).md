
# Employee Salary Prediction System

## Project Overview

The Employee Salary Prediction System is a Machine Learning project designed to predict employee salaries based on various factors such as age, education level, years of experience, skills score, certifications, job role, and company type.

The objective of this project is to understand the complete machine learning workflow, including data generation, preprocessing, exploratory data analysis, visualization, model training, evaluation, and salary prediction.

---

## Dataset Generation / Loading Process

A synthetic dataset containing 2500 employee records was generated using Python libraries such as NumPy and Pandas.

The dataset includes the following features:

* Age
* Education
* Experience
* SkillsScore
* Certifications
* JobRole
* CompanyType
* Salary (Target Variable)

Salary values were generated using realistic factors such as experience, education level, skills score, certifications, job role, and company type. Missing values and duplicate records were intentionally added to demonstrate data preprocessing techniques.

---

## Libraries Used

The following Python libraries were used in this project:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

Machine Learning Algorithms:

* Random Forest Regressor

Evaluation Metrics:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Steps to Run the Project

1. Generate the employee dataset.
2. Perform data preprocessing:

   * Handle missing values
   * Remove duplicate records
   * Encode categorical features
   * Scale numerical features
3. Perform Exploratory Data Analysis (EDA).
4. Create visualizations for salary trends and feature relationships.
5. Split the dataset into training and testing sets.
6. Train the Random Forest Regression model.
7. Evaluate the model using MAE, RMSE, and R² Score.
8. Run the salary prediction system and provide employee details as input.
9. Obtain the predicted employee salary.

---

## Key Insights from Analysis

* Employees with more years of experience generally earn higher salaries.
* Higher education levels such as Master's and PhD tend to receive higher salaries.
* Job roles significantly influence salary levels.
* Skills score and certifications positively impact employee salaries.
* Company type also contributes to salary variation.
* Experience and skills score showed strong positive correlation with salary.

---

## Model Performance Summary

The Random Forest Regressor was used to predict employee salaries.

Evaluation Metrics Used:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

The model achieved strong prediction performance and was able to accurately estimate salaries based on employee attributes.

---

## Project Files

* Employee_Salary_Prediction.ipynb
* employee_salary_dataset.csv
* processed_employee_salary.csv
* README.md

---

## Author

Aashish kotha

Machine Learning Internship Project – Infobharat Interns

