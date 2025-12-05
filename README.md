🧼📊 Sales Analytics – Python Data Cleaning + Power BI Executive Dashboard

This project demonstrates a complete end-to-end analytics workflow: starting from a messy raw sales dataset, cleaning and transforming it using Python, and building a multi-page Power BI dashboard that delivers executive-level insights into sales, profit, product performance, and customer behavior.

The final deliverable is a polished business intelligence solution that reflects real-world BI practice across data cleaning, modeling, visualization, and analytical storytelling.

🚀 Project Overview

The goal of this project is to convert raw, inconsistent sales data into a clean, structured dataset and an interactive analytical dashboard designed for business decision-makers.

The workflow includes:

Cleaning and preprocessing the dataset in Python

Exporting a clean dataset for BI usage

Designing a multi-page Power BI dashboard

Creating KPI summaries, visual analytics, and drill-down insights

Applying consistent UI/UX styling across all pages

🧹 Data Cleaning (Python)

Notebook: notebooks/data_cleaning.ipynb
Cleaned dataset: data/cleaned_sales.csv

The raw dataset contained:

Missing values

Inconsistent numeric formats

Incorrect data types

Currency values stored as text

Mixed-format dates

Duplicates and invalid rows

Using Pandas and NumPy, the cleaning steps included:

Import and schema inspection

Type correction for dates, numbers, and categorical fields

Handling missing and invalid values

Cleaning and converting currency fields

Renaming columns for consistency

Removing duplicates

Exporting a clean dataset ready for Power BI

The cleaned dataset is the single source of truth for all Power BI visuals.

📊 Power BI Dashboard

The dashboard is designed with a consistent dark-theme UI, focusing on clarity, interactivity, and executive readability.
It is structured across three analytical pages, each with a distinct purpose.

🔷 Page 1 — Retail Sales Overview

A high-level executive snapshot of the business, including:

Total Sales

Total Profit

Profit Margin %

Average Order Value

Sales by Country

Sales by Product Line

Top Customers

Time-based sales trend (year, month, day)

Interactive slicers for Year and Country

This page is optimized for quick decision-making and stakeholder presentations.

🔷 Page 2 — Detailed Analytics

A deeper analysis of performance patterns over time, products, and customers:

Sales trend by Month

Profit by Product Line

Year-over-Year Sales comparison

Profit vs Profit Margin % visualization

Customer performance table (Sales & Profit)

Product line summary table (Sales, Profit, Margin %)

This page supports diagnosis, pattern discovery, and operational analysis.

🔷 Page 3 — Contribution Analysis

A breakdown of the underlying drivers of sales performance using advanced visuals:

Waterfall Chart (Total Sales contribution by Product Line)

Sales by Country (bar chart)

Treemap (Country × Product Line contribution)

Interactive drill-downs using slicers

Replaces earlier AI visuals (Key Influencers, Decomposition Tree) for better design and clarity

This page showcases contribution patterns and highlights key sales drivers.

🛠 Tools & Technologies

Python

Pandas

NumPy

Google Colab

Power BI

Data modeling

DAX measures

KPI visuals

Waterfall charts

Bar and line charts

Treemap

Slicers & drill-through interactions

Custom layout design (PowerPoint background)

Other Tools

PowerPoint (dashboard background design)

GitHub for version control and documentation


🎯 Key Outcomes

Built a fully interactive, business-grade analytics dashboard

Cleaned and modeled raw data for BI usage

Identified top-performing countries, products, and customers

Analyzed monthly and yearly sales patterns

Designed a polished, visually consistent UI/UX across all pages

Demonstrated an end-to-end BI workflow used in real industry projects
