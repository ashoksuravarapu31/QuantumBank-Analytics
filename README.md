🚀 QuantumBank Analytics

A Python-powered Banking Analytics System for Data Insights & Reporting

This project provides end-to-end banking analytics using:

Python ETL Pipelines

SQLite Database

Data Cleaning & Transformation Scripts

Power BI Interactive Dashboard

Visualizations (Matplotlib / Seaborn)

The goal is to analyze customer, loan, credit card, and transaction data with accurate reporting and insights.

⭐ Features
🧹 ETL & Data Processing

Clean raw CSV/SQLite data

Remove duplicates & handle missing values

Merge datasets for unified analytics

Generate final processed datasets

📊 Banking Analytics

Customer Age Distribution

Credit Card Type Distribution

Loan Amount Distribution

Transaction Trend Over Time

📈 Dashboards (Power BI)

Customer Insights

Loan Analysis

Credit Card Usage

Transaction Behavior

🛢️ SQLite Database Operations

Create tables

Import datasets

Validate schema

Run SQL-based reporting

🧱 Tech Stack
Layer	Technologies
Data Processing	Python, Pandas, NumPy
Database	SQLite3
Visualization	Matplotlib, Seaborn
Dashboard	Power BI
Scripting	Python ETL Pipelines
📂 Project Structure
QuantumBank-Analytics/
│
├── data/  
│   ├── bank360.db  
│   ├── customers.csv  
│   ├── loans.csv  
│   ├── credit_cards.csv  
│   ├── transactions.csv  
│   ├── bank360_final_output.csv  
│   ├── full_merged_banking_data.csv  
│   └── full_merged_banking_data_from_sqlite.csv  
│
├── scripts/  
│   ├── bank360_main.py  
│   ├── bank360_pipeline.py  
│   ├── bank360_analysis.py  
│   ├── sqlite_create_tables.py  
│   ├── sqlite_import_data.py  
│   └── sqlite_verify.py  
│
├── visuals/  
│   ├── credit_card_type_distribution.png  
│   ├── customer_age_distribution.png  
│   ├── loan_amount_distribution.png  
│   └── transaction_amount_trend.png  
│
├── BANK360_Report.pbix  
├── bank360.sqbpro  
└── README.md  

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/ashoksuravarapu31/QuantumBank-Analytics.git

2️⃣ Install Python Dependencies
pip install pandas matplotlib seaborn

3️⃣ Create SQLite Database
python scripts/sqlite_create_tables.py

4️⃣ Import Data into SQLite
python scripts/sqlite_import_data.py

5️⃣ Verify Tables
python scripts/sqlite_verify.py

6️⃣ Run the ETL Pipeline
python scripts/bank360_pipeline.py

7️⃣ Generate Visualizations
python scripts/bank360_analysis.py

🎯 Insights Generated

Customer demographics

Spending patterns

Credit card usage type distribution

Age-based segmentation

Loan category analysis

Transaction behavior over time

📸 Visualizations
💳 Credit Card Type Distribution

👥 Customer Age Distribution

💰 Loan Amount Distribution

📉 Transaction Amount Trend Over Time

📊 Power BI Dashboard

Contains professional analytical reports including:

Customer Segmentation

Loan Insights

Credit Card Trends

Transaction Behavior Trends

File: BANK360_Report.pbix

👨‍💻 Developed By

Ashok Suravarapu
BCA Graduate
Aspiring Data Analyst / Python Developer

📄 License

MIT License
