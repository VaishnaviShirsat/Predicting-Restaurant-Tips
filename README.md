# Predicting-Restaurant-Tips
Business Analytics project using Microsoft Excel to analyze restaurant tipping patterns through data cleaning, visualization, correlation analysis, and regression modeling.
## Project Objective
  
The objective of this project is to analyze restaurant customer data and build a regression model capable of predicting the tip amount based on customer characteristics such as:
- Gender
- Smoking Status
- Day of Visit
- Meal Time
- Party Size
- Total Bill
The insights can help restaurant managers improve customer service and make informed business decisions.
## Problem Statement

Restaurant management wants to understand which customer factors influence tipping behavior.

Using Excel, the project:

- Cleans the dataset
- Encodes categorical variables
- Creates Pivot Tables
- Builds Charts
- Performs Correlation Analysis
- Develops a Multiple Linear Regression model
- Predicts future tip amounts
## Dataset Information

Source: Business Analytics with Excel Certification Project

Rows: 244

Columns:
- Sex
- Smoker
- Day
- Time
- Size
- Total Bill
- Tip

Target Variable
Tip

Independent Variables
- Sex
- Smoker
- Day
- Time
- Size
- Total Bill
## Tools Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- IF Functions
- CORREL Function
- Regression Analysis ToolPak
- Data Cleaning
## Project Workflow

1. Data Cleaning
2. Missing Value Check
3. Duplicate Removal
4. Convert Categories into Numeric Values
5. Pivot Table Analysis
6. Pie Chart Creation
7. Bar Chart Creation
8. Correlation Analysis
9. Multiple Regression Analysis
10. Tip Prediction

## Dashboard

The Excel dashboard includes:

- Gender-wise Tip Distribution
- Tips by Gender and Meal Time
- Regression Results
- Correlation Analysis
- Predicted Tips

## Key Insights

• Higher total bills generally result in higher tips.
• Dinner customers tend to leave larger tips than lunch customers.
• Party size has a positive relationship with tipping.
• Total Bill is the strongest predictor of tip amount.
• Gender and smoking status have comparatively smaller effects on tipping behavior.

## Regression Model

Multiple Linear Regression was performed using Excel Data Analysis ToolPak.

General Equation:

Predicted Tip =
Intercept
+ β₁(Sex)
+ β₂(Smoker)
+ β₃(Day)
+ β₄(Time)
+ β₅(Size)
+ β₆(Total Bill)

The coefficients were obtained from the regression output and used to calculate predicted tips.

## Project Files

📄 Problem Statement

📊 Dataset

📑 Project Report

🖼 Dashboard Images

📉 Regression Analysis

## Results

The developed regression model successfully estimates restaurant tip amounts based on customer characteristics. The project demonstrates practical business analytics techniques using Microsoft Excel, helping restaurant managers understand customer tipping behavior and improve decision-making.

## Future Improvements

- Develop an interactive Power BI Dashboard
- Build the prediction model in Python
- Compare Linear Regression with Machine Learning algorithms
- Deploy the model as a web application




