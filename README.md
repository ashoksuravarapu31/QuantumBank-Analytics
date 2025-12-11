🚀 QuantumBank Analytics

A Python-Driven Banking Data Analysis & Reporting Platform

This project provides end-to-end banking analytics using Python ETL pipelines, SQLite database, and Power BI dashboards for deep financial insights.

The system includes:

Automated data cleaning

Dataset merging & transformation

Customer demographics analytics

Loan & credit card insights

Transaction behavior study

Visualization charts

Interactive Power BI reporting

⭐ Features
🧹 ETL & Data Processing

Clean raw datasets

Remove duplicates

Standardize fields

Merge CSVs into a unified dataset

📊 Analytics Provided

Customer Age Analysis

Credit Card Type Distribution

Loan Amount Patterns

Transaction Trend Over Time

📈 Dashboards

Power BI Interactive Reporting

Visual insights for management

Trend charts & behavior analysis

🧱 Tech Stack
Layer	Technologies
Data Processing	Python, Pandas, NumPy
Database	SQLite
Visualization	Matplotlib, Seaborn
Reporting	Power BI
Automation	Python Scripts
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

⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/ashoksuravarapu31/QuantumBank-Analytics.git

2️⃣ Install Dependencies
pip install pandas matplotlib seaborn

3️⃣ Create Database
python scripts/sqlite_create_tables.py

4️⃣ Import Data
python scripts/sqlite_import_data.py

5️⃣ Verify Database
python scripts/sqlite_verify.py

6️⃣ Run Data Pipeline
python scripts/bank360_pipeline.py

7️⃣ Generate Visuals
python scripts/bank360_analysis.py

📸 Visualizations
💳 Credit Card Type Distribution

👥 Customer Age Distribution

💰 Loan Amount Distribution

📉 Transaction Amount Trend

📊 Power BI Interactive Dashboard

File: BANK360_Report.pbix
Includes:

Customer Segmentation

Loan Performance

Transaction Patterns

Credit Card Insights

👨‍💻 Developed By

Ashok Suravarapu
BCA Graduate
Aspiring Data Analyst & Python Developer

📄 License

MIT License
