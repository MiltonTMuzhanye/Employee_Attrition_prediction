Employee Attrition Prediction
Project Overview
This project predicts which employees are likely to leave the company. It helps HR departments take action early to retain valuable staff and reduce turnover costs.

Business Problem
Employee turnover is expensive and disruptive. This system helps:

Identify at-risk employees before they leave
Understand why employees leave
Develop targeted retention programs
Save recruitment and training costs

Dataset
We use IBM HR Analytics data with:
1,470 employees
31 features including:
Personal details (age, income, education)
Job factors (role, satisfaction, overtime)
Company experience (years at company, promotions)
Work-life balance indicators
Attrition Rate: 16% (237 employees left out of 1,470)

What This Project Does
1 Data Preparation
Encodes categorical variables (department, job role, etc.)
Removes constant columns that don't help prediction
Scales numerical features for better model performance

2 Data Analysis
Shows attrition patterns across departments
Identifies key factors linked to employees leaving
Reveals overtime has strong impact on attrition

3 Prediction Models
We test four machine learning models:

Logistic Regression - Good balance of performance
Accuracy: 75.5%
Recall: 76.6% (catches most employees who leave)

Random Forest - High accuracy but misses leavers
Accuracy: 83.7%
Recall: 6.4% (misses most employees who leave)

XGBoost - Good overall performance
Accuracy: 84.0%
Recall: 31.9%

CatBoost - Best balanced performance Best Model
Accuracy: 85.4%
Recall: 46.8%
Precision: 55.0%

4 Model Performance
Model	Accuracy	Precision	Recall	F1-Score
Logistic Regression	75.5%	37.1%	76.6%	50.0%
Random Forest	83.7%	42.9%	6.4%	11.1%
XGBoost	84.0%	50.0%	31.9%	39.0%
CatBoost	85.4%	55.0%	46.8%	50.6%

Key Results
Best Model: CatBoost
Identifies 47% of employees who will leave
55% of flagged employees actually leave
85% overall accuracy

Key Findings
Overtime strongly linked to attrition
Younger employees and lower income employees more likely to leave
Sales department has highest attrition rate
Job satisfaction and work-life balance are important factors

Business Impact
Cost Savings Calculation
Average cost to replace employee: $50,000
Employees identified as leaving: 22 out of 47
Potential savings: 22 × $50,000 = $1,100,000

Actionable Insights
Focus retention efforts on employees working overtime
Review compensation for high risk departments
Improve work life balance programs
Target career development for at-risk employees
