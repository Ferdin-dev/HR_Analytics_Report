# HR Analytics Report

## Project Overview

This project involved the collection, cleaning, and analysis of HR data in order to identify trends and patterns and make recommendations for improvement. The data included employee performance reviews, compensation data, and turnover data.

![Dashboard 1](https://github.com/Ferdin-dev/HR_Analytics_Report/assets/55439765/a6abcf7b-0b13-493a-844b-966e3ed1e88a)

## Table of Contents
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data cleaning preparation](#data-cleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Difficulties](#difficulties)
- [Screenshots](#screenshots)
- [Demo](#demo)


## Data Sources
HR Analytics Data: The primary dataset used for this analysis is the “hr_analytics.csv” file, containing detailed information about the company employee.

## Tools
- Excel – Data cleaning
- SQL Server – Data Analysis
- Power BI – Creating reports

## Data cleaning preparation

In the initial data preparation phase, we performed the following tasks:
- Imported the data to SQL Server
- Data loading and inspection in Power BI
- Handling missing values and errors
- Data cleaning and formatting

## Exploratory Data Analysis

EDA involved exploring the HR data to answer key questions, such as:
- Is there a correlation between the distance employees commute and attrition?
- What is the overall job satisfaction level among employees?
- Do employees who have been with the company longer tend to stay?
- Does work-life balance have an impact on attrition?

## Data Analysis

Include some interesting code/features worked with:

### SQL Code

Total employee
```
SELECT COUNT(EmployeeCount) as Total_employee
FROM HR_Employee_Attrition
```

Total male
```
SELECT COUNT(EmployeeCount) as Total_Male
  FROM HR_Employee_Attrition
  where Gender = 'Male
```

Total Female
```
SELECT COUNT(EmployeeCount) as Total_Female
  FROM HR_Employee_Attrition
  where Gender = 'Female'
 ```

## Results

The analytics results are summarized as follows:
- The work-life balance doesn’t impact on attrition
- The rate of job satisfaction is high at job satisfaction level 4
- The attrition percentage doesn’t have much impact on the distance from home.

## Recommendations

Based on the analysis, we recommend the following actions:
- Reduce the attrition percentage impact on the distance from home
- The increase the rate of job satisfaction in other levels too.


## Difficulties

I had a problem with data type when I was trying to import the CSV file into SQL Server, the program says can’t convert string data type into float. So, I used another data type to get the final result.

## Screenshots

![Project_1_Dashboard_1](https://github.com/Ferdin-dev/HR_Analytics_Report/assets/55439765/9a3e500b-b5b9-4bb2-aeb9-a95d45951c39)
![Project_1_Dashboard_2](https://github.com/Ferdin-dev/HR_Analytics_Report/assets/55439765/7ebd51a0-0e8d-452b-8792-299527cc40fd)
![Dashboard 3](https://github.com/Ferdin-dev/HR_Analytics_Report/assets/55439765/78079210-197b-4891-aff5-d00563962382)


## Demo
https://github.com/Ferdin-dev/HR_Analytics_Report/assets/55439765/59065d2b-66de-4117-9c4e-59d50292536f


