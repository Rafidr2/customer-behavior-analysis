# 📊 Customer Shopping Behavior Analysis

**End-to-End Data Analytics Project**

## Overview

This project simulates a real-world, end-to-end data analytics workflow. Starting from a raw Excel dataset, the project demonstrates how data analysts clean, explore, analyze, and visualize data to generate actionable business insights. The workflow mirrors how data is handled in a corporate environment, from Python-based analysis to SQL querying and executive-level reporting.

---

## Dataset

* **Source:** Customer shopping transaction data
* **Rows:** ~3,900 records

**Features include:**

* Customer demographics (age, gender, location, subscription status)
* Purchase details (product, category, price, season, size, color)
* Shopping behavior (discounts, shipping type, purchase frequency, ratings)

The dataset is stored in the `/data` folder.

---

## Tools & Technologies

* **Python (Jupyter Notebook, pandas)** – Data loading, cleaning, and EDA
* **PostgreSQL & pgAdmin 4** – SQL-based data analysis
* **Power BI** – Interactive dashboard and visualization
* **Gamma** – Business presentation (PowerPoint)
* **Excel** – Original raw dataset

---

## Project Steps

### 1️⃣ Data Loading & Exploratory Data Analysis (Python)

* Loaded the Excel dataset into Jupyter Notebook using pandas
* Inspected data structure and summary statistics
* Identified missing values and data quality issues

### 2️⃣ Data Cleaning & Feature Engineering

* Handled missing values using appropriate imputation methods
* Standardized column names for readability
* Created new features such as customer age groups and purchase frequency
* Removed redundant or unnecessary columns

### 3️⃣ Database Integration

* Connected Jupyter Notebook to a PostgreSQL server
* Loaded the cleaned dataset into PostgreSQL using pgAdmin
* Verified data integrity after import

### 4️⃣ SQL Analysis

* Wrote SQL queries to answer self-defined business questions, including:

  * Revenue by customer demographics
  * Subscriber vs. non-subscriber spending behavior
  * Top-performing products and categories
  * Impact of discounts and shipping types
  * Customer segmentation based on purchase history

SQL scripts are available in the `/sql` folder.

### 5️⃣ Dashboard & Reporting

* Built an interactive Power BI dashboard to visualize trends and KPIs
* Summarized findings in a written analysis report
* Created a professional presentation using Gamma to communicate insights and recommendations

---

## Dashboard

The Power BI dashboard highlights:

* Revenue distribution by customer segment
* Product and category performance
* Subscription and loyalty trends
* Key purchasing behaviors that drive revenue

The interactive Power BI file (`.pbix`) and a preview image are available in the `/dashboard` folder.
Dashboard visuals are also included in the PDF report and PowerPoint presentation.

---

## Results & Business Insights

* Identified high-value customer segments and loyal buyers
* Analyzed the effectiveness of discounts and subscriptions
* Highlighted top-rated and most-purchased products
* Developed data-driven recommendations for marketing and customer retention strategies

---

## How to Run This Project

1. Clone the repository
2. Open the Jupyter Notebook in the `/notebooks` folder
3. Install required Python libraries:

   ```bash
   pip install pandas psycopg2 sqlalchemy
   ```
4. Update database connection credentials in the notebook
5. Run the notebook to clean data and load it into PostgreSQL
6. Execute SQL queries from the `/sql` folder
7. Open the Power BI file in the `/dashboard` folder to explore the dashboard

---

## Notes

This project was created for learning and portfolio purposes to demonstrate practical data analytics skills, including Python, SQL, data visualization, and business communication.

---
