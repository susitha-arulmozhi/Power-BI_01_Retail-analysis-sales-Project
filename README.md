# Retail Sales Analysis Power BI Project

## Project Overview

**Project Title**: Retail Sales Analysis  
**Level**: Beginner  
**File name**: `01_Retail sales analysis.pbix`

This project aims to showcase the capabilities and methodologies employed by data analysts in Power BI for examining, refining, and interpreting retail sales information. It is particularly suited for beginners in data analysis who wish to establish a strong proficiency in Power BI.


## Objectives

1. **Establish a Retail Sales Database: Construct a retail sales database**: The dataset is `SQL - Retail Sales Analysis_utf.csv`
2. **Data Cleansing**: Detect and eliminate records that contain missing or null values.
3. **Perform Business Analysis**: Utilize Power BI to respond to targeted business queries and extract meaningful insights from the sales data.

## Project Structure

### 1. Dataset cleaning

**a. Promote First Row as Headers:**

In Power BI, when you load data, sometimes the first row of your dataset contains the column headers. To promote this row as the headers, go to the "Home" tab in the Power Query Editor and click on "Use First Row as Headers." This action will convert the first row of data into the column names.

**b. Rename the Column Names:**

To rename columns, select the column you wish to rename in the Power Query Editor. Right-click on the column header and choose "Rename," or double-click the column header. Enter the new name for the column and press Enter. This step helps in making the column names more meaningful and easier to understand.

**c. Check and Change the Data Types:**

Ensuring that each column has the correct data type is crucial for accurate data analysis. In the Power Query Editor, you can see the current data type of each column next to the column name. To change a data type, click on the data type icon and select the appropriate type (e.g., text, number, date). This step ensures that Power BI processes the data correctly.

**d. Use Detect Data Types:**

Power BI offers a feature to automatically detect data types. In the Power Query Editor, go to the "Transform" tab and click on "Detect Data Type." Power BI will analyze the data in each column and assign the most appropriate data type. This feature can save time and ensure that data types are set correctly.

**e. Remove Null Values in All Columns:**

To clean your dataset by removing rows with null values, select the columns you want to clean in the Power Query Editor. Go to the "Home" tab, click on "Remove Rows," and then choose "Remove Blank Rows." Alternatively, you can filter out null values by clicking on the drop-down arrow in the column header, unchecking the "null" option, and clicking "OK." This step ensures that your dataset is free from incomplete records, which can affect analysis accuracy.

### 2. Create the visuals

**I. Cards:** 
1. Number of customers
2. Total Sales
3. Number of transactions

**II. Filters:**  
1. Date
2. Age
3. Gender
4. Category
   
**III. Pie Chart:**
1. Number of customers by category

**IV. Line Chart:**
1. Sales by month and year

**V. Column Chart:**
1. Sales by category
2. Transactions by gender

**VI. Area Chart:**
1. Sales by Age

## Findings

- **Number of customers**: There are a total of 155 unique customers
- **Total sales**: The total sales during the period is 908K
- **Number of transactions**: The total number of transactions is 1987
- **High-Value Transactions**: Numerous transactions exceeded a total sale amount of $1000. These transactions signify luxury purchases.
- **Sales Trends**: A monthly review of sales data reveals fluctuations. This analysis enables the identification of peak sales periods.

## Conclusion

This project serves as a comprehensive introduction to Power BI for data analysts, covering data import, data transformation, exploratory data analysis, and business-driven visualizations. The insights derived from this project can help drive business decisions by understanding sales patterns, customer behavior, and product performance.

## How to Use

1. **Clone the Repository**: Clone this project repository from GitHub.
2. **Download the dataset**: Download the dataset `SQL - Retail Sales Analysis_utf.csv` to to your local computer and import to Power BI
3. **Explore and Modify**: Feel free to modify the queries to explore different aspects of the dataset or answer additional business questions.

## Author - Susitha Arulmozhi

This project is part of my portfolio, showcasing the Power BI skills essential for data analyst roles. If you have any questions, feedback, or would like to collaborate, feel free to get in touch!

- **LinkedIn**: [Connect with me professionally](https://www.linkedin.com/in/susitha-a)

Thank you for your support, and I look forward to connecting with you!
