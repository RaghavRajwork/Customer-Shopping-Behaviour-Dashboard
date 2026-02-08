# Customer-Shopping-Behaviour-Dashboard
📌 Project Overview
This project demonstrates a complete data lifecycle—from raw data ingestion and cleaning in Python to advanced behavioral analysis using SQL and interactive visualization in Power BI. The goal was to transform a dataset of 3,900+ customer records into actionable insights regarding shopping habits, demographics, and loyalty trends.

🛠️ Tech Stack
Language: Python 3.x

Libraries: Pandas, NumPy, SQLAlchemy, Matplotlib, Seaborn

Database: PostgreSQL

Visualization: Power BI

Environment: Jupyter Notebook (VS Code)

🚀 Key Features
1. Automated ETL Pipeline (Python)
Data Extraction: Ingested raw CSV data into a Pandas environment.

Intelligent Transformation: * Cleaned "Review Rating" nulls by applying category-specific medians.

Standardized schema naming conventions for seamless SQL integration.

Feature Engineering: Created age_group bins and mapped purchase_freq_days to convert categorical frequency into numeric intervals.

Database Loading: Built a high-performance bridge using SQLAlchemy to load the processed data into a PostgreSQL database.

2. Advanced SQL Analytics
Utilized PostgreSQL to uncover deeper business insights through:

CTEs & Window Functions: Ranked top-performing products within each category.

Customer Segmentation: Classified users into New, Returning, and Loyal cohorts based on purchase history.

Revenue Analysis: Calculated the percentage contribution of revenue by age group and gender.

3. Interactive Power BI Dashboard
Designed a user-centric dashboard to track:

Demographic Drivers: Visualized revenue gaps between male and female segments.

Loyalty Metrics: Analyzed the correlation between high previous purchase counts and subscription status.

Dynamic Filtering: Implemented year-based slicers and interactive category deep-dives.

📊 Key Business Insights
Target Demographics: Identified the specific age groups (Adult vs. Senior) that drive the highest average order value.

Retention Trends: Discovered that customers with 5+ previous purchases are significantly more likely to utilize promotional codes and subscriptions.

Product Performance: Mapped out the top 3 items per category, providing clear direction for inventory focus.

📂 Repository Structure
CSB.ipynb: Python notebook containing the ETL pipeline logic.

customer_shopping_behavior.sql: SQL scripts for behavioral analysis and segmentation.

customer_shopping_behavior.pbix: The standalone Power BI dashboard file.
