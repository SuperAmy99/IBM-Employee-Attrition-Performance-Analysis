# IBM-Employee-Attrition-Performance-Analysis

📌 Uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’. 

This is a fictional data set created by IBM data scientists.


## DATASET

[WA_Fn-UseC_-HR-Employee-Attrition.csv]([https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bc6f32a9-0024-4a3e-9e44-6690df275bf3/WA_Fn-UseC_-HR-Employee-Attrition.csv](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/)

## RESEARCH QUESTIONS:

1. What is the attrition rate for the company, and what are the factors that contribute to it?
2. Is there a relationship between distance from home and attrition, and does it vary by job role?
3. How does employee education level affect their monthly income, and does this impact attrition rates?
4. Are there any gender differences in job satisfaction, and does this impact attrition rates?
5. What factors are associated with employee performance ratings, and is there a relationship between performance ratings and attrition?
# DESCRIPTION
IBM is an American MNC operating in around 170 countries with major business vertical as computing, software, and hardware.
Attrition is a major risk to service-providing organizations where trained and experienced people are the assets of the company. The organization would like to identify the factors which influence the attrition of employees.

# Data Dictionary
- Age: Age of employee
- Attrition: Employee attrition status
- Department: Department of work
- DistanceFromHome
- Education: 1-Below College; 2- College; 3-Bachelor; 4-Master; 5-Doctor
- EducationField
- EnvironmentSatisfaction: 1-Low; 2-Medium; 3-High; 4-Very High
- JobSatisfaction: 1-Low; 2-Medium; 3-High; 4-Very High
- MaritalStatus
- MonthlyIncome
- NumCompaniesWorked: Number of companies worked prior to IBM
- WorkLifeBalance: 1-Bad; 2-Good; 3-Better; 4-Best
- YearsAtCompany: Current years of service in IBM
- 
# Analysis Task:
- Import attrition dataset and import libraries such as pandas, matplotlib.pyplot, numpy, and seaborn.
- Exploratory data analysis
  - Find the age distribution of employees in IBM
  - Explore attrition by age
  - Explore data for Left employees
  - Find out the distribution of employees by the education field
  - Give a bar chart for the number of married and unmarried employees
  - Build up a logistic regression model to predict which employees are likely to attrite.

# Libraries used:
- numpy
- pandas
- tensorflow
- matplotlib.pyplot
- patsy
- sklearn
- seaborn
