# Atlas Labs HR Analytics Report

## 📌 Table of Contents
1. [Introduction](#introduction)
2. [Dataset Overview](#dataset-overview)
3. [Data Preparation](#data-preparation)
   - [Data Inspection and Cleaning](#data-inspection-and-cleaning)
   - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
   - [Data Modeling](#data-modeling)
4. [Report Creation and Visualization](#report-creation-and-visualization)
   - [Overview](#overview)
   - [Demographics](#demographics)
   - [Performance Tracker](#performance-tracker)
   - [Attrition](#attrition)
5. [Key Findings & Insights](#key-findings--insights)
6. [How to Use This Project](#how-to-use-this-project)
7. [Future Work & Improvements](#future-work--improvements)
8. [References](#references)

## 📌 Introduction
This report aims to analyze employee performance, demographics, and attrition within **Atlas Labs** using **Power BI**. The dataset includes metrics such as employee performance ratings, satisfaction levels, and factors influencing employee retention.

## 📂 Dataset Overview
The dataset includes:
- **Fact Table:**
  - **PerformanceRatings**: Contains annual performance evaluation results.
- **Dimension Tables:**
  - **Employee**: Employee personal information.
  - **EducationLevel**: Employee education background.
  - **RatingLevel**: Performance rating levels.
  - **SatisfiedLevel**: Employee satisfaction levels.

## 🔄 Data Preparation

### **Data Inspection and Cleaning**
- Loaded the dataset into **Power BI Desktop**.
- Inspected and cleaned the data to remove duplicates, outliers, and errors.
- Renamed tables for better clarity and changed data types as needed.

### **Exploratory Data Analysis (EDA)**
- Conducted an initial exploration of the dataset to understand distributions and trends.
- Identified key patterns in employee performance, satisfaction, and attrition.
- Detected and visualized outliers that could impact HR decision-making.

### **Data Modeling**
- Created a **Dimension Date Table** for time intelligence in **DAX**.
- Established relationships between **FactPerformanceRating** and **DimSatisfiedLevel**, **DimRatingLevel**.
![Data Model](screenshots/data_model.jpg)

## 📈 Report Creation and Visualization

### **1️⃣ Overview**
- Displays key metrics:
  - **Total Employees**: Active employees vs. employees who have left.
  - **Employee Trends**: Trends of hires and attrition over the years.
  - **Department Breakdown**: Employees segmented by department and job role.

![Overview Screenshot](screenshots/overview_page.jpg)

### **2️⃣ Demographics**
- **Age Distribution**: Displays age distribution across employees.
- **Marital Status & Ethnicity**: Number of employees by marital status and average salary by ethnicity.

![Demographics Screenshot](screenshots/demographics_page.jpg)

### **3️⃣ Performance Tracker**
- **Employee Performance**: Details for each employee including start date, last review date, and next review date.
- **Performance Trends**: Trends in self-ratings, manager ratings, and satisfaction scores.

![Performance Tracker Screenshot](screenshots/perfomance_tracker_page.jpg)
- employee can be filtered by
![Employee Filter Screenshot](screenshots/employee_filter.jpg)

### **4️⃣ Attrition**
- **Factors Impacting Attrition**: Analyzes the factors influencing employee attrition such as department, overtime, travel frequency, and tenure.

![Attrition Screenshot](screenshots/attrition_page.jpg)

## 📌 Key Findings & Insights
- Insights into **employee performance trends**, **age distribution**, and **attrition factors**.
- Identification of **key drivers of employee satisfaction** and **factors influencing attrition**.
  
## ⚡ How to Use This Project

### **Power BI Report**
- Download the **hr_analytics_report_atlaslabs.pbix**.
- Open the file in **Power BI Desktop**.
- Interact with the report to explore detailed insights.

### **Using Cleaned Data**
- The cleaned data file (**cleaned_data.csv**) can be used for further analysis in Python, R, or SQL.

## 🚀 Future Work & Improvements
- **Expand dataset** to include employee feedback and exit interview data.
- Implement **predictive analytics** to forecast attrition trends.
- Perform **employee sentiment analysis** to assess workplace satisfaction.

## 🔗 References
- [DataCamp Dataset](https://www.datacamp.com)
