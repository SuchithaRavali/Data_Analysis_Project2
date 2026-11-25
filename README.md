# Data_Analysis_Project2
Olist Ecommerce Analytics Dashboard

## Project Overview

This project analyzes the Brazilian Olist e-commerce dataset using Power BI. The goal was to clean, model, and visualize business data to uncover insights related to sales, customers, products, sellers, payments, and customer reviews.

The project follows a standard analytics workflow:

1. Data Profiling
2. Data Cleaning & Validation
3. Data Modeling
4. DAX Measure Creation
5. Dashboard Development
6. Business Insights

## Dataset

Source: Olist Brazilian E-Commerce Dataset- Kaggle

The project uses the following datasets:

- Customers
- Orders
- Order Items
- Payments
- Reviews
- Products
- Sellers
- Category Translation
- Geolocation

Total records analyzed: Over 1 million rows across all tables.

## Tools Used

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

### 1. Data Profiling

The first phase focused on understanding the structure and quality of the data before making any modifications.

Activities Performed:

- Imported all datasets into Power BI
- Reviewed table structures and column definitions
- Enabled column profiling tools in Power Query

Examined: 

- Missing values
- Errors
- Distinct values
- Data distributions
- Potential key columns
- Identified data quality issues requiring further review
  
Outcome:

- Understanding of each dataset
- Identification of missing values and validation requirements
- Documentation of profiling findings


### 2. Data Cleaning & Validation

The second phase focused on validating data quality and preparing the datasets for analysis and modeling.

Activities Performed: 

- Verified and corrected data types across all tables
- Investigated data quality anomalies
- Reviewed missing values and null records
- Validated data against expected business rules

Examined:

- Missing category values
- Missing delivery dates
- Product dimension completeness
- Payment anomalies
- Review score validity
- Geographic coordinate validity
- Delivery timeline consistency
  
Outcome:

- Data quality issues investigated and documented
- Critical business rules validated
- Datasets prepared for relationship modeling and analysis


### 3. Data Modeling

The third phase focused on connecting the datasets and building a relational model to support analysis and reporting.

Activities Performed

- Created relationships between related tables in Model View
- Verified relationship cardinality and filter direction
- Identified fact and dimension tables
- Organized the model to support analytical queries

Established Relationships

- Customers → Orders
- Orders → OrderItems
- Orders → Payments
- Orders → Reviews
- Products → OrderItems
- Sellers → OrderItems
- CategoryTranslation → Products

Outcome

- Connected datasets through business keys
- Established a logical fact-dimension model
- Created a foundation for DAX calculations and dashboard development


### 4. DAX Measure cretion

The fourth phase focused on creating reusable business metrics to support reporting and dashboard development.

Activities Performed:

- Created a dedicated Measures Table
- Developed KPI measures using DAX
- Applied appropriate formatting to measures
- Prepared metrics for dashboard visualizations
  
Measures Created

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Total Freight Cost
- Average Review Score
- Delivered Orders
- Cancelled Orders
- Delivery Success Rate
- Revenue Per Customer
  
Outcome

- Reusable business metrics established
- Consistent calculations across reports
- Foundation created for dashboard development

### 5. Dashboard development



## Learning Outcomes

Through this project, I practice:

- End-to-end Power BI development
- Data quality assessment
- Business-focused data modeling
- Dashboard design
- Analytical problem solving

This project was being created as part of my data analytics portfolio to demonstrate practical Power BI, Power Query, and business intelligence skills.

