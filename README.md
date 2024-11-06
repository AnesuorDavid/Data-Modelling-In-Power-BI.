# Data-Modelling-In-Power-BI.
Here we conducted a Data Modelling Excercise. Here I cleaned the data, normalised it, extracted insights using aggregated tables and came up with the required solutions.
Adventure Works Sales and Inventory Optimization
In this project, I focused on optimizing Adventure Works' data model to address stagnating sales and inventory issues. Using Power BI, I built and fine-tuned a data model by optimizing data types, configuring relationships, and enhancing performance. Here’s an overview of the steps taken to optimize the data model and improve decision-making for the company.

Steps Taken
1. Imported Data Model
Downloaded and imported the AdventureWorksSales.pbix Power BI report.
Accessed the Data view to begin the process of data optimization.
2. Optimized Data Types
Customers Table: Adjusted data types for columns to ensure accuracy and efficiency:
Name, Surname, Location, Membership Tier, Customer Source: Set to Text.
Date of Birth: Set to Date.
Phone Number: Set to Text.
Orders Table: Optimized the following columns:
Order Total, Discounts, Shipping Fee: Set to Decimal Number.
Order ID, Customer ID, Product ID, Order Quantity: Set to Whole Number.
Order Date: Set to Date.
Order Status, Payment Method, Billing Address, Tracking Number: Set to Text.
3. Built and Configured Model Relationships
Created a One-to-many relationship between the Customers and Orders tables using the Customer ID field.
Set the relationship’s cardinality to One-to-many with a Single cross-filter direction for data consistency.
4. Disabled Auto Date/Time
Disabled the Auto Date/Time feature to manually manage date-time performance and maximize model efficiency.
5. Saved and Applied Changes
Applied all changes to the data model and ensured the performance was optimized.
