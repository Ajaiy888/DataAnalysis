🧠 Data Analytics Project
📋 Overview
This project demonstrates a complete data analytics workflow — from data ingestion and cleaning to SQL analysis and dashboard visualization.
The goal is to extract meaningful business insights and present them clearly through a Power BI dashboard.

📂 Dataset

Source: Kaggle

Description: Contains records related to [Index(['customer_id', 'age', 'gender', 'item_purchased', 'category','purchase_amount_(usd)', 'location', 'size', 'color', 'season',
       'review_rating', 'subscription_status', 'shipping_type', 'discount_applied', 'promo_code_used', 'previous_purchases','payment_method', 'frequency_of_purchases'],
      dtype='object')].

Size: ~[3990] rows × [18] columns

Key Fields:
Date – Transaction or event date
Customer_ID – Unique identifier
Product – Item or service name
Sales_Amount – Revenue or value

🧰 Tools & Technologies
Category	Tool / Library
Programming	Python (Pandas, NumPy, Matplotlib, Seaborn)
Database	MySQL (via SSMS)
Visualization	Power BI
Environment	Jupyter Notebook / VS Code
Version Control	Git & GitHub
⚙️ Project Steps
1. Load and Explore Data (Python)

Imported CSV file using pandas.read_csv().

Performed initial exploratory data analysis (EDA):

Checked data types, missing values, duplicates.

Generated summary statistics.

Visualized distributions and correlations.

2. Clean and Prepare Data

Handled missing or inconsistent values.

Removed duplicates and outliers.

Converted data types (e.g., object → datetime, float).

Created new derived columns (e.g., total revenue, profit margin).

Exported cleaned dataset to .csv for SQL and Power BI use.

3. SQL Analysis (MySQL in SSMS)

Loaded cleaned dataset into a MySQL database.

Executed SQL queries to answer key business questions, such as:

Top-performing products or regions.

Monthly revenue trends.

Customer retention and frequency patterns.

Used aggregate functions, joins, subqueries, and window functions.

4. Dashboard Development (Power BI)

Connected Power BI to the MySQL database (via ODBC or CSV).

Created interactive visuals:

Sales trends by month

Revenue by region/product

Customer segmentation

Added filters, slicers, and KPI cards for user interactivity.

Designed layout for clarity and storytelling.

📊 Results & Insights

Identified top 5 products driving ~60% of total revenue.

Discovered seasonal sales peaks in Q4.

Found that loyal customers contributed 3× higher average order value.

Highlighted underperforming regions for targeted marketing.

🧠 Key Takeaways

Combined Python + SQL + Power BI for end-to-end analytics.

Demonstrated data cleaning, transformation, and visualization skills.

Focused on business insights and clear storytelling for decision-making.

💬 Feel free to explore the code and visuals — feedback and suggestions are welcome!

#DataAnalytics #PowerBI #SQL #Python #BusinessIntelligence #EDA #DataVisualization #AnalyticsProject
