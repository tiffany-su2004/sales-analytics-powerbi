🧼📊 Sales Analytics – Python Data Cleaning + Power BI Executive Dashboard

This project demonstrates a complete end-to-end analytics workflow — starting from a messy raw sales dataset, cleaning it using Python, and building a multi-page Power BI dashboard that delivers executive-level insights into sales performance, profit trends, product contribution, and customer behavior.

🚀 Overview

The goal of this project is to transform unstructured sales data into a polished analytical report that supports business decision-making.
The workflow includes:

Cleaning and preprocessing the raw data in Python

Exporting a clean dataset for analytics

Designing an interactive Power BI dashboard

Visualizing key KPIs and deep-dive analytics

This project reflects real-world BI and data analysis practices used in industry.

🧹 Data Cleaning (Python)

Notebook:
➡️ notebooks/data_cleaning.ipynb

The raw dataset contained issues such as:

Missing values

Encoding errors

Incorrect data types

Inconsistent number formats

Unstructured date fields

Using Pandas, I performed:

Dataset import and preview

Data type correction

Missing value handling

Cleaning currency & numeric fields

Renaming and formatting columns

Detecting invalid or duplicate records

Exporting the cleaned dataset for Power BI

The cleaned dataset used in the dashboard:
➡️ data/cleaned_sales.csv

📊 Power BI Dashboard

The dashboard is designed for business users and contains multiple pages, each focused on a different analytical domain.

1️⃣ Executive Overview

Total Sales

Total Profit

Profit Margin %

Average Order Value

Sales by Country

Sales by Product Line

Top Customers

Time-based sales trend

2️⃣ Analytics Page

Sales by Month

Profit by Product Line

Year-over-Year Sales Trend

Profit vs Profit Margin comparison

Customer-level performance table

Product line contribution analysis

3️⃣ AI Insights Page

Key Influencers visual

Top Segments

Decomposition Tree with drill-downs

Country-level breakdown

Dashboard file (zipped for GitHub):
➡️ dashboard/SalesDashboard.pbix.zip



🛠 Tools & Technologies

Python (Google Colab)

Pandas

NumPy

Power BI

Data modeling

DAX measures

AI visuals (Key Influencers, Decomposition Tree)

Slicers & drill-down interactions

GitHub

Version control

Project documentation
