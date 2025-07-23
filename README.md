🛒 Zepto E-Commerce SQL Data Analyst Portfolio Project
This portfolio project is based on a real-world e-commerce inventory dataset scraped from Zepto — one of India’s fastest-growing quick-commerce startups. It simulates a data analyst's workflow: from raw data cleaning and transformation to delivering business-driven insights using SQL.

🎯 Why This Project?
As a Data Analyst aspirant, this project helped me build hands-on skills in:
Writing clean, optimized SQL queries
Performing real-world Exploratory Data Analysis (EDA)
Delivering insights around pricing, stock, and category performance
Structuring an end-to-end data project for interviews and portfolios
Whether you're prepping for interviews in e-commerce, product, or retail analytics, this project gives a practical edge.

📁 Dataset Overview
The dataset was sourced from Kaggle and contains SKU-level inventory data scraped from the Zepto app. Each row represents a unique product variant with attributes like price, weight, availability, and category.

🔸 Key Columns:
sku_id: Unique product identifier
name: Product title
category: Item classification (e.g. Fruits, Beverages, Snacks)
mrp & discountedSellingPrice: Prices (converted from paise to ₹)
discountPercent: Discount on MRP
availableQuantity: Inventory stock
outOfStock: Stock availability (boolean)
weightInGms: Product weight

🛠️ Project Workflow
Here’s a snapshot of what was done using PostgreSQL:

1️⃣ Database Setup
Created a normalized zepto table using appropriate datatypes
Imported and cleaned the dataset (handled encoding & nulls)

2️⃣ Exploratory Data Analysis
Checked distinct categories, stock availability, and product duplication
Investigated null values and inconsistent pricing

3️⃣ Data Cleaning
Removed rows with invalid or missing price data
Converted price columns from paise to rupees for clarity

4️⃣ Business-Focused Insights
🔟 Top products with highest discounts

🚫 High-MRP items that are out of stock
💸 Estimated revenue potential by category
🧮 Products with high price but low discount (luxury items)
📦 Inventory grouped by weight (Low, Medium, Bulk)
⚖️ Price-per-gram calculation to evaluate product value
📊 Top 5 categories by average discount %
📊 Tools & Technologies Used
SQL (PostgreSQL) – Core querying, data cleaning, aggregations
pgAdmin – SQL environment for executing scripts
Excel/Notepad++ – For pre-cleaning CSV and fixing encoding

🚀 What I Learned
This project taught me how to:

Think like a business analyst by asking the right data questions
Write clean and scalable SQL cod
Translate messy real-world data into actionable insights
Simulate how analysts support decision-making in retail/e-commerce settings

🎥 Project Walkthrough
Follow this YouTube tutorial to walk through the full project and replicate each step.

💼 About Me
Hi, I'm Felixjudwin Nadar — an aspiring Data Analyst passionate about solving business problems using data.
This project is part of my data analytics portfolio aimed at showcasing my SQL and business intelligence skills for real-world use cases.

📩 Let's connect on LinkedIn
📁 Explore more of my work on GitHub
