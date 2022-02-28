# Sales-analysis-Project

# The Case Study
We need to improve our internet sales reports and want to move from static reports to visual dashboards.
Essentially, we want to focus it on how much we have sold of what products, to which clients and how it has been over time.
Seeing as each sales person works on different products and customers it would be beneficial to be able to filter them also.
We measure our numbers against budget so I added that in a spreadsheet so we can compare our values against performance. 
The budget is for 2022 and we usually look 2 years back in time when we do analysis of sales.

# Business Request & User Stories
The business request for this data analyst project was an executive sales report for sales managers. Based on the request that was made from the business we following user stories were defined to fulfill delivery and ensure that acceptance criteria’s were maintained throughout the project.

![image](https://user-images.githubusercontent.com/63034550/155961738-24390517-6367-4550-8c58-4583b82f4570.png)
# Data Cleansing & Transformation (SQL)
To create the necessary data model for doing analysis and fulfilling the business needs defined in the user stories the following tables were extracted using SQL.

One data source (sales budgets) were provided in Excel format and were connected in the data model in a later step of the process.

Below are the SQL statements for cleansing and transforming necessary data.
Cleansing Fact_Internetsales.sql
Cleansing DIM_Product.sql
Cleansing DIM_Date.sql
Cleansing DIM_Customer.sql
# Data Model
Below is a screenshot of the data model after cleansed and prepared tables were read into Power BI.

This data model also shows how FACT_Budget has been connected to FACT_InternetSales Table and other necessary DIM tables.
![image](https://user-images.githubusercontent.com/63034550/155963063-b07f4f07-f846-4b0e-a92b-f8e38e34e939.png)
# Sales Management Dashboard
The finished sales management dashboard with one page with works as a dashboard and overview, with two other pages focused on combining tables for necessary details and visualizations to show sales over time, per customers and per products.
- Sales Overview
![image](https://user-images.githubusercontent.com/63034550/155964905-ff7152bf-98e2-4ea0-a4ab-8aaf6a503570.png)
- Customer Details
![image](https://user-images.githubusercontent.com/63034550/155964966-ba8b9018-ef65-4ff5-ad05-f4d1ed56865a.png)
- Product Details
![image](https://user-images.githubusercontent.com/63034550/155965045-3ea2b0f9-5c4c-4c84-8b52-33d3b6475975.png)





