# IBM-Employee-Attrition-Performance-Analysis

IBM, a multinational corporation operating in over 170 countries and specializing in computing, software, and hardware, recognizes attrition as a common challenge that companies globally must address for improvement. The organization is actively focused on understanding the factors that contribute to employee attrition.

Our objective is to identify and analyze these factors influencing employee attrition and subsequently construct a machine-learning model capable of predicting whether an employee is likely to leave or remain with the company.

Please note that this is a fictional data set created by IBM data scientists.


# DATASET

[WA_Fn-UseC_-HR-Employee-Attrition.csv]([https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bc6f32a9-0024-4a3e-9e44-6690df275bf3/WA_Fn-UseC_-HR-Employee-Attrition.csv](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/)

# Analysis Task:

- Data Preparation:

  Import the attrition dataset and necessary libraries, including pandas, matplotlib.pyplot, numpy, and seaborn.

- Exploratory Data Analysis (EDA):

  - Explore attrition based on age.
  - Investigate attrition patterns by gender.
  - Examine the distribution of employees across different education fields.

- Hypothesis Testing:

  Formulate and test two hypothesis to gain insights into factors influencing attrition.

- Machine Learning Model:

  - Develop a machine-learning model to predict employee attrition.
  - Evaluate and choose the best-performing model based on relevant metrics.

- Dashboard Creation in Tableau:

  - Utilize Tableau to create an interactive dashboard.
  - Showcase key insights, visualizations, and model predictions related to employee attrition.

# Data Dictionary
- Age: Age of employee
- Attrition: Employee attrition status(whether an employee has left the company)
- BusinessTravel: Non-Travel; Travel-Frequently; Travel-Rarely
- DailyRate: Daily pay rate of an employee
- Department: Department of employee
- DistanceFromHome: The distance from the employee's home to the workplace
- Education: 1-Below College; 2- College; 3-Bachelor; 4-Master; 5-Doctor
- EducationField: The field of education of the employee
- EmployeeCount: The count of employee
- EmployeeNumber: The unique number of the employee
- EnvironmentSatisfaction: 1-Low; 2-Medium; 3-High; 4-Very High
- Gender: Gender of the employee
- HourlyRate: Hourly pay rate of an employee
- JobInvolvement: 1-Low; 2-Medium; 3-High; 4-Very High
- Job Level: The level of an employee
- Job Role: The role of the employee in the company
- JobSatisfaction: 1-Low; 2-Medium; 3-High; 4-Very High
- MaritalStatus: Marital status of the employee
- MonthlyIncome: The monthly income of the employee
- MonthlyRate: Monthly pay rate of an employee
- NumCompaniesWorked: Number of companies worked prior to IBM
- Over18: Whether the employee is over 18
- OverTime: Whether the employee works overtime
- PercentSalaryHike: The percentage of salary hike
- PerformanceRating: 1-Low; 2-Good; 3-Excellent; 4-Outstanding
- RelationshipSatisfaction: 1-Low; 2-Medium; 3-High; 4-Very High
- StandardHours: Standard working hours
- StockOptionLevel: Level of stock options
- TotalWokingYears: Total years of working experience
- TrainingTimesLastYear： Number of training times last year
- WorkLifeBalance: 1-Bad; 2-Good; 3-Better; 4-Best
- YearsAtCompany: Current years of service in IBM
- YearsInCurrentRole：Years in the current role
- YearsSinceLastPromotion：Years since the last promotion
- YearsWithCurrManager：Years with the current manager


# Libraries used:
- numpy
- pandas
- matplotlib.pyplot
- sklearn
- seaborn
- pymysql
- statsmodels
- scipy
- imbalanced-learn
