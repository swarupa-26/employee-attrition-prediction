# employee-attrition-prediction
Employee attrition refers to the rate at which employees leave a company over time. High attrition negatively impacts productivity, business continuity, team performance, and hiring cost. This project uses Machine Learning techniques to identify employees who are likely to leave the organization, enabling HR teams to take preventive action.

 Key Features of the Project
 End-to-End ML Pipeline
Data Cleaning
Feature Engineering
Exploratory Data Analysis (EDA)
Model Training
Hyperparameter Tuning
Model Evaluation

✔Technologies Used
Python
Pandas, NumPy,Matplotlib, Seaborn,Scikit-Learn
XGBoost


Dataset
The dataset contains employee information such as:
Age,Gender,Department,Job Role,Education,Marital Status,Monthly Income,Work-Life Balance,Job Satisfaction,Distance From Home,OverTime,Years at Company,Training Frequency,Attrition (target variable)

Target variable:
Attrition → Yes / No (Binary Classification)

Methodology
1. Data Preprocessing
Handled missing values
Encoded categorical variables using One-Hot Encoding
Scaled numerical columns using StandardScaler

2. EDA Insights
Employees doing OverTime are more likely to leave
Low income employees tend to attrite more
Low Job Satisfaction & Environment Satisfaction strongly correlate with attrition
Younger employees (25–35) leave more often

3. Model Building
Models tested:
Logistic Regression
Decision Tree
Random Forest

Accuracy: ~92%
Handles non-linearity well
Works great with tabular employee data

Key Output
Predicts whether an employee will leave (Yes) or stay (No)
Highlights major factors influencing attrition
Provides HR teams insights to improve retention
