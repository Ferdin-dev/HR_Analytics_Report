# HR Analytics Report

## Project Overview

This project involved the collection, cleaning, and analysis of HR data in order to identify trends and patterns and make recommendations for improvement. The data included employee performance reviews, compensation data, and turnover data.

![Dashboard 1](https://github.com/Ferdin-dev/HR_Analytics_Report/assets/55439765/a6abcf7b-0b13-493a-844b-966e3ed1e88a)

## Table of Contents

## Data Sources
HR Analytics Data: The primary dataset used for this analysis is the “hr_analytics.csv” file, containing detailed information about the company employee.

## Tools
- Excel – Data cleaning
- SQL Server – Data Analysis
- Power BI – Creating reports

## Data cleaning/preparation

In the initial data preparation phase, we performed the following tasks:
- Imported the data to SQL Server
- Data loading and inspection in Power BI
- Handling missing values and errors
- Data cleaning and formatting

## Exploratory Data Analysis (EDA)

EDA involved exploring the HR data to answer key questions, such as:
- Is there a correlation between the distance employees commute and attrition?
- What is the overall job satisfaction level among employees?
- Do employees who have been with the company longer tend to stay?
- Does work-life balance have an impact on attrition?

## Data Analysis

Include some interesting code/features worked with:

### SQL Code

Total employee
`SELECT COUNT(EmployeeCount) as Total_employee
FROM HR_Employee_Attrition
`

Total male
`SELECT COUNT(EmployeeCount) as Total_Male
  FROM HR_Employee_Attrition
  where Gender = 'Male
  '
`
Total Female
`SELECT COUNT(EmployeeCount) as Total_Female
  FROM HR_Employee_Attrition
  where Gender = 'Female'
  `

