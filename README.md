
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

🔗 **Tableau Public Dashboard:** https://public.tableau.com/app/profile/ayaan.ahmad5861/viz/EmployeeAttritionModel_17728739837750/EmployeeAttritionModel#1



## Business Insights
- Overtime is highly correlated with Attrition. Those who have been given overtime have a 56% more chance of attritioning than those who haven't.
  HR Recommendation: Give less overtime to employees. More focus should be given on proper workload management.
- Senior level employees are less likely to attrition while junior level employees are more likely to attrition. 22 year old employees have the highest risk of attrition.
  HR Recommendation: Incentives should be given to junior level employees to continue with the company. Counselling sessions should be conducted to show career   growth if they stay with the company
- Satisfaction score and work life balance score are negatively correlated with attrition.
  HR Recommendation: Ensure high satisfaction and work life balance score amongst all employees.
- Those employees who have not been promoted in the last 5 years have a 92% more chance of attrition than those who have.
  HR Recommendation: Promotion policy should be made more lenient and more number of promotional opportunities should be granted to employees to reduce attrition.
- 9% of current employees are under "High Risk" of attrition.
- Sales and Engineering departments have the highest number of high risk employees while HR department has the least.

## Top 19 employees at risk of attrition:
- EMP1860
- EMP0976
- EMP3427
- EMP8893
- EMP5090
- EMP8539
- EMP1343
- EMP3705
- EMP9004
- EMP3776
- EMP8538
- EMP7580
- EMP9152
- EMP3340
- EMP8993
- EMP3601
- EMP5390
- EMP9010
- EMP9672

## Tools Used
- Python (Pandas, NumPy)
- Matplotlib
- Seaborn
- Scikit-learn
- Tableau Public
- GitHub
