# Customer-Behavior-Analysis
This data analysis project explores customer shopping behavior using a dataset of 3,900 transactions to uncover patterns in spending, customer loyalty, product performance, and business drivers.

🚀 Project Objective

To analyze customer data and answer key business questions such as:

Which categories generate the most revenue?
Do loyal or subscribed customers spend more?
How do discounts and payment methods influence spending?
What customer segments drive the most value?
📂 Dataset Overview
Rows: 3,900 customers
Features: 18+ columns
Includes:
Demographics (Age, Gender, Location)
Transaction data (Category, Item, Purchase Amount)
Behavioral data (Previous Purchases, Subscription Status)
Experience metrics (Review Rating, Shipping Type)
🧹 Data Processing (Python)

Key steps:

Handled missing values in review_rating using median imputation by category
Standardized column names to snake_case
Created new features:
age_group (quartile-based segmentation)
purchase_frequency_days (converted categorical frequency)
Removed redundant columns

📌 Result: Clean, analysis-ready dataset exported to MySQL

🗄️ SQL Analysis

Performed structured queries to derive business insights:

Revenue comparison by gender
Customer segmentation:
New, Returning, Loyal
Subscription impact on spending
Discount effectiveness
Top-performing products by rating and volume
Shipping and payment behavior

📌 Focus: Business-driven queries, not just basic aggregation

📊 Power BI Dashboard

Interactive dashboard showcasing:

🔹 KPIs
Total Customers: 3900
Total Revenue: $233K
Average Rating: 3.75
🔹 Visuals
Revenue by Category
Sales Distribution
Subscription Breakdown
Payment Method Usage (with gender split)
Geographic Sales Map
Age Group Analysis
📈 Key Insights
Clothing dominates revenue → Primary business driver
Subscribers spend more on average → Monetization opportunity
Discounts increase spending → Effective strategy
Loyal customers contribute disproportionately → Retention is key
Digital payments dominate usage → Align with fintech trends
🧠 Business Recommendations
Focus marketing on high-performing categories (Clothing)
Increase subscription adoption through targeted campaigns
Build loyalty programs for repeat customers
Expand strong-performing products geographically
Use discounts strategically to boost revenue
⚙️ Tech Stack
Python: Pandas, NumPy
SQL: MySQL
Visualization: Power BI
Data Pipeline: SQLAlchemy
