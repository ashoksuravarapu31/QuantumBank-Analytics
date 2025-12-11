# 🚀 QuantumBank Analytics

A Modern Banking Analytics System using Python ETL, SQLite, and Power BI.

# 📊 Project Overview

QuantumBank Analytics processes banking customer data, performs automated ETL using Python, and generates insights such as:

Customer age demographics

Credit card usage trends

Loan amount distribution

Transaction behavior analysis

Power BI dashboards for executive reporting

# 🛠️ Tech Stack
| **Layer**        | **Technologies**              |
| ---------------- | ----------------------------- |
| ETL & Processing | Python, Pandas, NumPy         |
| Database         | SQLite                        |
| Visualization    | Matplotlib, Seaborn, Power BI |
| Automation       | Python Scripts                |


# 📂 Project Structure

QuantumBank-Analytics/
│
├── data/
│   ├── bank360.db
│   ├── bank360_final_output.csv
│   ├── credit_cards.csv
│   ├── customers.csv
│   ├── full_merged_banking_data.csv
│   ├── full_merged_banking_data_from_sqlite.csv
│   ├── loans.csv
│   └── transactions.csv
│
├── scripts/
│   ├── bank360_analysis.py
│   ├── bank360_main.py
│   ├── bank360_pipeline.py
│   ├── sqlite_create_tables.py
│   ├── sqlite_import_data.py
│   └── sqlite_verify.py
│
├── visuals/
│   ├── credit_card_type_distribution.png
│   ├── customer_age_distribution.png
│   ├── loan_amount_distribution.png
│   ├── loan_status_count.png
│   └── transaction_amount_trend_over_time.png
│
├── BANK360_Report.pbix
├── bank360.sqbpro
├── .gitattributes
└── README.md



# 📸 Visual Outputs (Python Analytics)

🔹 Credit Card Type Distribution

🔹 Customer Age Distribution

🔹 Loan Amount Distribution

🔹 Loan Status Count

🔹 Transaction Amount Trend Over Time

# 📸 Power BI Dashboard Screenshots

📊 Overview Dashboard

👥 Customer Insights

💰 Loan Insights

# ⚙️ Installation & Running

1️⃣ Install Required Libraries
pip install pandas numpy matplotlib seaborn sqlite3

2️⃣ Create Database & Tables
python scripts/sqlite_create_tables.py

3️⃣ Import Data
python scripts/sqlite_import_data.py

4️⃣ Run Full ETL Pipeline
python scripts/bank360_pipeline.py

5️⃣ Run Main Analytics Script
python scripts/bank360_main.py

# 👨‍💻 Developed By

Ashok Suravarapu
BCA Graduate | Fresher
Aspiring Data Analyst / Python Developer

# 📜 License

MIT License






