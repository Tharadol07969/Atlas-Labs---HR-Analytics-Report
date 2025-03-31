# Atlas Labs HR Analytics Report

## Overview
The goal of this project is to build a comprehensive report using fictitious datasets from a tech company named Atlas Labs. The HR team at Atlas Labs aims to monitor key metrics related to employees. This dataset was sourced from DataCamp and includes the following:

### Fact Table
- **PerformanceRatings**: Collects information about the results of the annual employee evaluation.

### Dimension Tables
- **Employee**: Employee information.
- **EducationLevel**: Education level.
- **RatingLevel**: Rating level.
- **SatisfiedLevel**: Employee satisfaction level.

## Data Preparation
1. **Data Inspection and Cleaning:**
   - Loaded the dataset into Power BI Desktop.
   - Inspected and cleaned the data to ensure there were no duplicates, outliers, or errors.
   - Changed the data types to appropriate types and renamed the tables for better clarity.

   ![Data Cleaning](./1.jpg)

2. **Data Modeling:**
   - Created a dimension date table to use the time intelligence functions in DAX, enabling continuous data display even if the fact table does not contain data for every date.
   - Established relationships between tables in the data model.

   ![Data Model](./2.jpg)

   The relationships between the `FactPerformanceRating` table and the `DimSatisfiedLevel` and `DimRatingLevel` tables were established multiple times due to the columns that can be linked to the respective dimension tables.

## Report Creation and Visualization
### 1. Overview
   - **Total Employees**: Displays the total number of employees, both active and those who have left the company.
   - **Employee Trends**: Shows trends in employee hires and attrition by year.
   - **Department Breakdown**: Visualizes the breakdown of employees by department and job role.

   ![Overview](./3.jpg)

### 2. Demographics
   - **Age Distribution**: Displays the youngest and oldest employees, and the distribution of ages.
   - **Marital Status and Ethnicity**: Shows the total employees by marital status and average salary by ethnicity.

   ![Demographics](./4.jpg)

### 3. Performance Tracker
   - **Employee Performance**: Tracks performance metrics for each employee, including start date, last review date, and next review date.
   - **Performance Trends**: Visualizes trends in self-ratings, manager ratings, and satisfaction scores.

   ![Performance Tracker](./5.jpg)

   - **Employee Filter**: Allows filtering of employees to view specific performance details.

   ![Employee Filter](./6.jpg)

### 4. Attrition
   - **Factors Impacting Attrition**: Analyzes factors that contribute to employee attrition, including department, travel frequency, overtime, and tenure.

   ![Attrition](./7.jpg)

## Conclusion
You can download the `.pbix` file to explore more details of the report. Thank you for reviewing the Atlas Labs HR Analytics Report.
