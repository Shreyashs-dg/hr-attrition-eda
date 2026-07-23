# hr-attrition-eda
Exploratory Data Analysis on IBM HR Employee Attrition dataset

## Dataset
Source: [IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## Column Categorization

**Target:** Attrition

**Categorical (text):** BusinessTravel, Department, EducationField, Gender, 
JobRole, MaritalStatus, Over18, OverTime

**Continuous numeric:** Age, DailyRate, DistanceFromHome, HourlyRate, 
MonthlyIncome, MonthlyRate, NumCompaniesWorked, PercentSalaryHike, 
TotalWorkingYears, TrainingTimesLastYear, YearsAtCompany, YearsInCurrentRole, 
YearsSinceLastPromotion, YearsWithCurrManager

**Ordinal (rating scales stored as int):** Education, EnvironmentSatisfaction, 
JobInvolvement, JobLevel, JobSatisfaction, PerformanceRating, 
RelationshipSatisfaction, StockOptionLevel, WorkLifeBalance

**Constant (no info, drop later):** EmployeeCount, StandardHours

**Identifier (not a feature):** EmployeeNumber