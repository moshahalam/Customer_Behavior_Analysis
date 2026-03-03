📊 Customer Shopping Behavior Analysis
📌 Overview
This data analytics project explores customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover insights into spending patterns, customer segmentation, product preferences, and subscription behavior to support data-driven business decisions.
The project demonstrates end-to-end analytics workflow — from data cleaning and SQL analysis to dashboard visualization and reporting.
📂 Dataset
Source: Customer transactional dataset
Records: 3,900 purchases
Key Fields:
Customer demographics (age, gender)
Product details (category, SKU, ratings)
Purchase information (total price, discount applied)
Subscription status
Shipping type
The dataset was cleaned and transformed before analysis.
🛠 Tools & Technologies
Python (Pandas, NumPy, Matplotlib/Seaborn) – Data loading, cleaning, EDA
SQL (PostgreSQL / MySQL / SQL Server) – Data querying and aggregation
Power BI – Interactive dashboard creation
Gamma – Presentation (PPT) creation
Jupyter Notebook – Analysis workflow
🔎 Project Steps
1️⃣ Data Loading & Cleaning (Python)
Imported dataset using Pandas
Handled missing values
Converted data types
Removed duplicates
Created new calculated columns
Prepared data for SQL and BI analysis
2️⃣ Exploratory Data Analysis (EDA)
Analyzed spending distribution
Identified top-performing product categories
Examined customer age segmentation
Evaluated discount usage trends
Studied subscription behavior
3️⃣ SQL Analysis
Performed advanced queries in PostgreSQL/MySQL/SQL Server:
Revenue by product category
Discount impact analysis
Customer segmentation queries
Identifying unsold products
Ranking top-performing items
Average spending comparisons
4️⃣ Power BI Dashboard
Built an interactive dashboard including:
Total Revenue KPI
Average Spending per Customer
Revenue by Category
Subscription vs Non-subscription comparison
Age Group Revenue Analysis
Shipping Preference Insights
Top Rated & Best-Selling Products
📊 Dashboard Features
Dynamic filters (Age, Category, Subscription Status)
KPI Cards for quick performance overview
Bar charts & trend visuals
Customer segmentation analysis
Interactive slicers
📈 Key Results & Insights
Identified high-revenue age segments
Determined top-performing product categories
Found relationship between discounts and purchase frequency
Highlighted subscription impact on total revenue
Discovered shipping preference trends
These insights can guide marketing strategy, pricing decisions, and customer retention initiatives.
▶️ How to Run the Project
🔹 Python Analysis
Open Data_cleaning.ipynb in Jupyter Notebook
Install required libraries:
pip install pandas numpy matplotlib seaborn
Run all cells
🔹 SQL Queries
Open Customer_Behavior.sql in PostgreSQL / MySQL / SQL Server
Execute queries against the cleaned dataset
🔹 Power BI Dashboard
Open the .pbix file in Power BI Desktop
Refresh data if needed
Interact with filters and visuals
📁 Project Structure
├── Data_cleaning.ipynb
├── Customer_Behavior.sql
├── PowerBI_Dashboard.pbix
├── Final_Report.pdf
└── README.md
💼 Why This Project Matters
This project showcases:
End-to-end data analytics workflow
Data cleaning & transformation skills
Advanced SQL querying
Business insight generation
Professional dashboard development
Reporting & presentation skills
It demonstrates the ability to convert raw transactional data into actionable business insights.
