# Credit Card Churn Analysis & Risk Intelligence Platform

An end-to-end data analytics project examining a 25-column credit card churn dataset to uncover behavioral patterns, customer friction points, and financial drivers of attrition across a portfolio of over 10,000 accounts.

---

Project Overview
Customer attrition represents a core revenue leakage point in retail banking. This project implements a complete data pipeline—from raw data ingestion and cleaning in Python to exploratory data analysis (EDA) using advanced SQL window functions in MySQL Workbench, culminating in an interactive web-based visualization dashboard deployed via GitHub Pages.

Total Portfolio Size: 10,127 accounts
Overall Portfolio Churn Rate: 16.07% (1,627 attrited vs. 8,500 active customers)
Total Portfolio Transaction Volume: $44,600,182.00



---




Tech Stack & Architecture
Data Processing & Cleaning: Python (Pandas, NumPy) inside Jupyter Notebook environments.
Database & Exploratory Data Analysis: MySQL Workbench (`credit_card_db`, `churn_data` table utilizing window functions, CTEs, and Conditional Aggregations).
Front-End Dashboard: HTML, CSS, JavaScript (With the Developing Authority of Google Gemini's Canvas ) deployed live on GitHub Pages.





---





Key Analytical Findings & SQL Insights
1. Support Friction Correlation: Attrition spikes significantly among accounts logging **4 or more customer service contacts** within a 12-month window, pointing to unresolved service friction as a primary defection trigger.
2. Revolving Balance Drop-Off:   Active cardholders carry substantially higher revolving balances, whereas customers trending toward churn exhibit sudden balance contraction prior to account closure.
3. High-Limit Passive Accounts:  A cluster of accounts maintain high credit limits ($15,000) paired with minimal annual transaction counts ($20), representing underutilized capital and elevated credit exposure risk.




---







Repository Structure

├── Credit Card Data Cleaned.csv      # Cleaned and processed multi-sheet dataset
├── Credit Card Data.csv              # Raw, uncleaned source dataset
├── JUPYTERCreditCardData.ipynb       # Python data cleaning and inspection script
├── SQLScriptCreditCardProject.sql    # Complete MySQL schema creation and 30-step EDA queries
├── index.html                        # Interactive front-end analytics dashboard
└── README.md                         # Project documentation
