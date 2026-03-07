
# HR Attrition Model

## Business Problem
The management team aims to predict whether an employee will leave the company and identify key drivers.  
Given limited capital and increasing investor crowding, the goal is to prioritize following questions:
- Which employees are most likely to leave?
- Does overtime increase attrition risk?
- Does low satisfaction cause attrition?
- How do promotions affect attrition?
- Which departments lose employees most often? Does it have a role to play in attrition?
  

## Objective
- Develop a data-driven Logistic Regression model and Random Forest model to predict whether an employee will leave the company or not.
- Develop an interactive dashboard for stakeholders to view the statistics.

## Dataset
The dataset contains data of 10,000 employees with attributes including:
- Employee age
- Department of work
- Stage of work (seniority)
- Tenure
- Monthly Income
- Satisfaction Score
- Work life balance score
- Overtime (Yes or No)
- Commute Distance
- Promotion in the last 5 years (Yes or No)
- Performance Score
- Total training hours in the last year
- Attrition (Yes or No)

## Methodology
1. Data cleaning and preprocessing using Python
2. Logistic Regression Model
3. Random Forest Model
4. Business Insights
5. Interactive dashboard development using Tableau

## Key Metrics
- Overtime (Yes or No)
- Promotion in the last 5 years (Yes or No)
- Performance Score
- Satisfaction Score

## Dashboard
The Tableau dashboard enables:
- Identification of top 20 at risk employees
- Identification of drivers of attrition such as promotion, overtime and satisfaction
- Distribultion of features by department, age and tenure

🔗 **Tableau Public Dashboard:** *(add link here)*

## 📁 Repository Structure
hr_attrition_model
│
├── data
│   └── Employee_Attrition_DataSet.csv
│
├── notebooks
│   └── attrition_analysis.ipynb
│   └── attrition_model.py
|
├── tableau
│   └── tableau_dashboard.twbx
│
├── outputs
│   └── feature_importance.png
│
└── README.md


## Business Insights


## Tools Used
- Python (Pandas, NumPy)
- Matplotlib
- Seaborn
- Scikit-learn
- Tableau Public
- GitHub
