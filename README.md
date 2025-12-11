)

📊 QuantumBank Analytics

A next-generation banking analytics system built with Python ETL pipelines, SQLite database, visualizations, and Power BI dashboards.

📘 1. Overview

QuantumBank Analytics transforms raw banking data into actionable insights.
It includes:

ETL pipeline to clean & merge datasets

Analytics on customers, loans, credit cards, and transactions

Visualization charts

Power BI dashboard for business reporting

⚙️ 2. Features
🔧 ETL Pipeline

Extracts data from CSV & SQLite

Cleans and validates datasets

Generates merged final dataset

Removes duplicates and missing values

📈 Data Analytics

Customer age distribution

Credit card type distribution

Loan amount analysis

Transaction trend analysis

📊 Dashboards

Power BI interactive report

Visual insights for management

📁 3. Project Structure
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

📚 4. Dataset Details
customers.csv

Contains customer demographics

Age

Region

Account type

loans.csv

Loan information

Loan type

Amount

Tenure

Status

credit_cards.csv

Credit card usage

Card type

Credit limit

transactions.csv

Transaction records

Amount

Timestamp

▶️ 5. How to Run the Project
Step 1: Install required packages
pip install pandas matplotlib seaborn

Step 2: Create SQLite database & tables
python scripts/sqlite_create_tables.py

Step 3: Import data into SQLite
python scripts/sqlite_import_data.py

Step 4: Verify imported data
python scripts/sqlite_verify.py

Step 5: Run ETL Pipeline
python scripts/bank360_pipeline.py

Step 6: Generate Analytics Charts
python scripts/bank360_analysis.py

📉 6. Visualizations
Credit Card Type Distribution

Customer Age Distribution

Loan Amount Distribution

Transaction Trend Over Time

📊 7. Power BI Dashboard

File available at:

BANK360_Report.pbix


Includes:

Loan analytics

Customer segmentation

Transaction patterns

Credit card insights

👨‍💻 8. Developed By

Ashok Suravarapu
BCA Graduate | Aspiring Data Analyst & Python Developer

📄 9. License

MIT License
Feel free to use and modify.

🎯 10. Future Enhancements (Optional Section)

Automating ETL with Airflow

Live dashboards with Streamlit

ML model for loan risk prediction

✅ This version is clean, professional
