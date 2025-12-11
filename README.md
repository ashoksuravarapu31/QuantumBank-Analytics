📊 Bank360 – End-to-End Banking Data Analytics Project

A complete Banking Data Engineering + Analytics project built using:

Python

SQLite database

ETL pipelines

Data Cleaning & Transformation

Matplotlib/Seaborn Visualizations

Power BI Dashboard

This project processes raw banking datasets and converts them into actionable insights with reports & dashboards.

🚀 Features
🔹 ETL Pipeline (Python)

Creates SQLite tables

Imports CSV datasets

Validates and cleans data

Generates transformed final dataset

🔹 Banking Analytics

Customer Age Analysis

Credit Card Distribution

Loan Amount Distribution

Transaction Trend Over Time

🔹 Dashboards

Interactive Power BI dashboard for management reporting

Charts for transaction behavior, age groups, loan patterns, etc.

🧱 Project Structure
Bank360/
│── data/
│     ├── customers.csv
│     ├── loans.csv
│     ├── credit_cards.csv
│     ├── transactions.csv
│     ├── bank360.db
│
│── scripts/
│     ├── bank360_main.py
│     ├── bank360_pipeline.py
│     ├── bank360_analysis.py
│     ├── sqlite_create_tables.py
│     ├── sqlite_import_data.py
│     ├── sqlite_verify.py
│
│── visuals/
│     ├── credit_card_type_distribution.png
│     ├── customer_age_distribution.png
│     ├── loan_amount_distribution.png
│     ├── transaction_amount_trend.png
│
│── BANK360_Report.pbix
│── README.md
│── .gitattributes

📂 Dataset Overview
Dataset	Contains
customers.csv	Customer demographics
loans.csv	Loan amounts & types
credit_cards.csv	Credit card types
transactions.csv	Transaction values & timestamps
📜 How to Run the Project
1️⃣ Install packages
pip install pandas matplotlib seaborn sqlite3

2️⃣ Create Database & Tables
python scripts/sqlite_create_tables.py

3️⃣ Import Data
python scripts/sqlite_import_data.py

4️⃣ Run Full ETL Pipeline
python scripts/bank360_pipeline.py

5️⃣ Generate Visualizations
python scripts/bank360_analysis.py

📈 Visualizations
🔹 Credit Card Type Distribution

🔹 Customer Age Distribution

🔹 Loan Amount Distribution

🔹 Transaction Trend Over Time

📊 Power BI Dashboard

The interactive dashboard is available in:

📄 BANK360_Report.pbix

Includes:

Loan analytics

Customer segmentation

Credit card usage

High-value transaction behavior

👨‍💻 Developed By

Ashok Suravarapu
BCA Graduate (Fresher)
Aspiring Data Analyst / Data Engineer

❤️ Now Your Final Step:
