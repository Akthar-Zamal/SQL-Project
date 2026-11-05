# SQL-Project
# E-Commerce Customer Churn Analysis Using MySQL

## 1. Project Overview

The **E-Commerce Customer Churn Analysis** project focuses on analyzing customer behavior and identifying factors that contribute to customer churn in an e-commerce business.

The project uses MySQL to store, clean, transform, and analyze customer data. SQL queries are used to identify customer trends, purchasing patterns, satisfaction levels, payment preferences, and churn behavior.

## 2. Project Objectives

- Analyze customer churn patterns.
- Identify factors influencing customer retention and churn.
- Understand customer purchasing behavior.
- Analyze customer satisfaction and complaints.
- Evaluate preferred login devices and payment methods.
- Identify customer segments with higher churn rates.
- Generate meaningful business insights using SQL queries.

## 3. Tools & Technologies

- **Database:** MySQL
- **IDE:** MySQL Workbench
- **Language:** SQL
- **Analysis Techniques:** Data Cleaning, Data Aggregation, Filtering, Grouping, Joins, Subqueries, CTEs, and Window Functions.

## 4. Database Information

**Database Name:** `ecomm`

**Table Name:** `customer_churn`

The customer_churn table contains the following columns:

| Column Name | Description |
|---|---|
| CustomerID | Unique customer identifier |
| Churn | Customer churn status |
| Tenure | Customer relationship duration |
| PreferredLoginDevice | Preferred login device |
| CityTier | Customer city category |
| WarehouseToHome | Distance from warehouse to home |
| PreferredPaymentMode | Preferred payment method |
| Gender | Customer gender |
| HourSpendOnApp | Time spent on the application |
| NumberOfDeviceRegistered | Registered devices |
| PreferedOrderCat | Preferred order category |
| SatisfactionScore | Customer satisfaction rating |
| MaritalStatus | Customer marital status |
| NumberOfAddress | Number of registered addresses |
| Complain | Whether the customer raised a complaint |
| OrderAmountHikeFromlastYear | Change in order amount |
| CouponUsed | Number of coupons used |
| OrderCount | Number of orders |
| DaySinceLastOrder | Days since the last order |
| CashbackAmount | Cashback received |

## 5. Project Workflow

### Step 1: Database Creation
- Created the `ecomm` database.
- Selected the database using the USE statement.

### Step 2: Table Creation
- Created the `customer_churn` table.
- Defined appropriate data types.
- Applied a primary key constraint to CustomerID.

### Step 3: Data Insertion
- Imported customer records into MySQL.
- Verified the inserted records.

### Step 4: Data Cleaning
- Identified and handled NULL values.
- Standardized inconsistent categorical values.
- Identified duplicate records.
- Corrected inconsistent payment methods and device categories.

### Step 5: Exploratory Data Analysis
- Analyzed total customers and churn distribution.
- Evaluated customer demographics.
- Examined payment preferences and order categories.
- Analyzed customer satisfaction and complaints.

### Step 6: SQL Analysis
- Aggregate functions
- GROUP BY and ORDER BY
- WHERE and HAVING
- CASE statements
- Joins
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions

## 6. Key Business Questions

1. What is the total number of customers?
2. How many customers have churned?
3. What is the overall customer churn rate?
4. Which gender has the highest churn?
5. Which payment method is most preferred?
6. Which product category has the highest customer orders?
7. Does customer satisfaction influence churn?
8. Do customer complaints contribute to churn?
9. Which city tier has the highest churn rate?
10. How does customer tenure affect churn?
11. Which customers have not placed orders recently?
12. What are the key factors affecting customer retention?

## 7. Expected Business Outcomes

- Identify high-risk customer segments.
- Understand factors associated with customer churn.
- Improve customer retention strategies.
- Identify customer satisfaction issues.
- Support data-driven business decisions.
- Help businesses develop targeted customer engagement strategies.

## 8. Project Files

| File Name | Description |
|---|---|
| E-Commerce Customer churn db.sql | Database creation, table creation, and data insertion SQL script |
| README.md | Project documentation |

## 9. How to Run the Project

1. Install MySQL Server and MySQL Workbench.
2. Open MySQL Workbench.
3. Import or open the `E-Commerce Customer churn db.sql` file.
4. Execute the SQL script to create the database and insert the records.
5. Select the database:

```sql
USE ecomm;
```

6. Verify the available tables:

```sql
SHOW TABLES;
```

7. View the customer records:

```sql
SELECT * FROM customer_churn;
```

8. Execute SQL queries to perform data cleaning and customer churn analysis.

## 10. Conclusion

This project demonstrates the practical application of SQL in solving business problems using customer data. Through data cleaning, exploratory analysis, and advanced SQL queries, the project aims to uncover customer behavior patterns and identify factors associated with customer churn.

**Skills Demonstrated:** MySQL, SQL, Data Cleaning, Data Analysis, Exploratory Data Analysis, Business Intelligence, and Problem Solving.

---

**Project Category:** SQL Data Analytics Project  
**Domain:** E-Commerce  
**Author: Patan Akthar Zamal**
