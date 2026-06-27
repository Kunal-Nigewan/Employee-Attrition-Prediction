# Employee Attrition Prediction using Machine Learning

## Overview

This project analyzes employee attrition patterns to identify the key factors influencing employees leaving an organization.
The project combines data preprocessing, exploratory data analysis (EDA), visualization, and machine learning models to generate meaningful HR insights and retention recommendations.

---

## Objective

* Analyze employee attrition trends
* Identify important factors affecting employee turnover
* Build predictive machine learning models
* Generate HR-focused business insights
* Recommend strategies to improve employee retention

---

## Dataset

Dataset Used: IBM HR Analytics Employee Attrition Dataset

Main Features:

* Age
* Department
* Job Role
* Monthly Income
* Overtime
* Work-Life Balance
* Job Satisfaction
* Years at Company
* Attrition (Target Variable)

---

## Project Workflow

### 1. Data Preprocessing

* Checked for missing/null values
* Removed unnecessary columns
* Converted Attrition values:

  * Yes = 1
  * No = 0
* Applied One-Hot Encoding to categorical columns
* Scaled numerical features using StandardScaler

### 2. Exploratory Data Analysis (EDA)

Performed multiple visualizations to understand:

* Attrition by Department
* Attrition by Job Role
* Attrition vs Monthly Income
* Attrition vs Work-Life Balance
* Attrition vs Years at Company
* Feature Importance Analysis
* ROC Curve Comparison

### 3. Machine Learning Models

Models Used:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

---

## Key Findings

* Employees working overtime showed significantly higher attrition.
* Lower monthly income was strongly associated with higher employee exits.
* Sales Representatives and Laboratory Technicians showed higher turnover compared to other roles.
* Employees with poor work-life balance had increased attrition rates.
* Most resignations occurred during the early years of employment.
* Younger employees showed slightly higher attrition trends.

---

## HR Recommendations

* Improve work-life balance initiatives across departments.
* Monitor overtime workload to reduce employee burnout.
* Conduct regular employee feedback sessions.
* Strengthen onboarding and engagement programs for newly joined employees.
* Encourage career growth and skill development opportunities.
* Identify high-risk employee groups for proactive retention efforts.

---

## Model Performance Summary

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 71.7%    |
| Random Forest       | 88.0%    |
| Gradient Boosting   | 87.0%    |

Random Forest achieved the highest overall prediction accuracy.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Repository Structure

```text
Employee-Attrition-Prediction/
│
├── analysis.ipynb
├── HR_Attrition.csv
├── Employee_Attrition_Report_KunalNigewan.pdf
├── README.md
└── graphs/
```

---

## Author

Kunal Nigewan
