#  SuperMart SQL Analytics Capstone Project

##  Project Overview
This project is a complete end-to-end SQL data analytics case study built using PostgreSQL. It simulates real-world retail business analysis for SuperMart, focusing on customer behaviour, employee performance, product trends, and revenue insights. The goal of this project is to demonstrate strong SQL skills in data cleaning, transformation, aggregation, joins, CTEs, and business reporting.

##  Tools Used
- PostgreSQL
- SQL (Advanced Queries)
- pgAdmin / PostgreSQL Workbench
- Relational Database Design Concepts
- Database Structure

##  The dataset consists of the following relational tables:
- customers
- orders
- order_items
- products
- categories
- employees
- regions
All tables are linked through primary and foreign key relationships.

##  Key Business Questions Solved
The project is structured into 10 progressive SQL tasks:

##  Task 1 — Data Retrieval & Filtering
- Extracted customer, product, and order information
- Applied filtering, sorting, and basic SELECT queries

##  Task 2 — Aggregations & Metrics
- Calculated total sales, profit, and averages
- Identified order status distribution
- Measured customer and product-level performance

##  Task 3 — Grouped Business Insights
- Analyzed customer registration trends
- Identified high-performing cities and products
- Measured employee productivity

##  Task 4 — Pattern Matching (LIKE / ILIKE)
- Filtered Gmail customers
- Identified product naming patterns (kits, combos, packs)
- Performed case-insensitive searches on city and names

##  Task 5 — Joins & Relationship Analysis
- Built full order-level reporting system
- Connected customers, employees, and products
- Measured employee handling performance
- Calculated product-level order frequency

##  Task 6 — CASE Statements (Business Segmentation)
- Classified products into Budget, Mid-range, Premium
- Segmented employee salary bands
- Categorized order values into High, Medium, Low tiers
- Built category-level price distribution analysis

##  Task 7 — Subqueries (Advanced Filtering)
- Identified products above average price
- Found customers with/without orders
- Extracted top-performing customers
- Built revenue comparison against averages

##  Task 8 — CTE-Based Analysis
- Customer revenue ranking system
- Best-selling products per category
- Monthly performance trends (2023)
- Customer frequency segmentation
- Year-over-year revenue analysis

##  Task 9 — Employee Performance Dashboard
- Built a full executive-level dashboard showing:
- Total delivered orders per employee
- Total revenue generated
- Average order value
- Best single order performance
- Performance classification:
- Elite
- Strong
- Developing
- Inactive

##  Task 10 — Customer Lifetime Value (CLV) Analysis
- Advanced customer segmentation system:
- Total orders per customer
- Delivered vs cancelled orders
- Lifetime revenue calculation
- Average order value
- Customer segmentation:
- VIP
- Loyal
- One-Time Buyer
- No Conversions
- Inactive

##  Key Insights
- A small percentage of customers generate the majority of revenue (VIP segment)
- Employee performance is highly uneven across regions
- Discounts significantly impact profit margins in some categories
- Several products remain consistently unpurchased (inventory inefficiency)
- Customer retention varies strongly by region and acquisition year

##  Business Impact
- This analysis can help SuperMart:
- Improve customer retention strategies
- Identify high-value customers for marketing campaigns
- Optimize employee performance evaluation
- Improve inventory and product pricing strategy
- Reduce losses from underperforming products

##  Skills Demonstrated
- SQL Joins (INNER, LEFT)
- Aggregations (SUM, COUNT, AVG)
- CTEs (Common Table Expressions)
- Subqueries (IN, EXISTS, derived tables)
- CASE statements for business logic
- Data segmentation & classification
- Analytical thinking & reporting

##  How to Run the Project
- Create PostgreSQL database
- Import all dataset tables
- Run SQL scripts in order (Task 1 → Task 10)
- Review outputs for insights
- Use queries for dashboards or reporting

##  Author
- Name:John Effiong
- Email: johnjohneffiong@gmail.com

##  Final Note
This project demonstrates end-to-end SQL analytical thinking — from raw data exploration to executive-level business insights.
