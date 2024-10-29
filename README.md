# LITA Capstone Project

### Project Title: Sales Performance Analysis for a Retail Store
[Project Overview](#project-overview) 

[Data Source](#data-source) 

[Tools Used](#tools-used) 

[Data Cleaning and Preparartions](#Data-Cleaning-and-Preparartions)

[Data Analysis](#data-analysis) 

[Data Visualizations](#data-visualization) 

---
### Project Overview
I am working on my LITA Project where I will analysis Sales Performance  for a Retail Store.I explored sales data to uncover key insights such as top-selling products, regional performance, and monthly sales trends. I produced an interactive Power BI dashboard that highlights these findings.

### Data Source
The Data was given by LITA team (Incubator Hub) on the learning platform (Canvas for Infrastructure) as an excel file.

### Tools Used
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. For Data Cleaning
  2. For Analysis
- SQL for Query Data [Download Here](https://www.microsoft.com)
- Power BI for Data Visualizations [Download Here](https://www.microsoft.com)
- GitHub for Portfolio Building

### Data Cleaning and Preparartions
The following was done to prepare our data for Analysis and Query
- Downloading of data from LITA LMS (Canvas)
- Opening of Data in Excel to Clean Dataset;
  1. Freezing Header Row
  2. Formatting Data as Table
  3. Checking for Blank Cells or Rows (None was found)
  4. Checking that each Row had the right Datatype
  5. Checking for Duplicate Rows
     - Downloaded Dataset had 50001 Rows including Header Rows
     - 40079 Duplicate Rows found and Removed
     - Cleaned Dataset left with 9921 Rows including Header Rows
  6. Added a Calcuated Column (Revenue) as Quantity Sold * Unitprice
- Copy data and opened in a New Workbook and saved it as a "csv" file
- Open Cleaned dataset csv file using Power BI to extract add new column to dataset from OrderDate Column:
  1. Added Column Year
  2. Added Column Month Name
  3. Added Column Quarter

### Exploratory Data Analysis

### Data Analysis
This is where we included some basic lines of code

```SQL
SElECT * FROM table1
WHERE CONDITION = TRUE
```
### Data Visualizations
![Sedentary_Mintues_Chart](https://github.com/user-attachments/assets/8bea7e60-78a4-4bca-9527-5b63a94fe558)
