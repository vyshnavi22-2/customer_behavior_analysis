Overview

This project demonstrates a complete data analytics workflow, including data loading, cleaning, exploratory analysis, SQL queries, and interactive visualization. The goal is to extract insights from the dataset and present them through a Power BI dashboard and a structured report.

Description: This project analyzes customer behavior in shopping environments to uncover patterns, trends, and insights that can help businesses make data-driven decisions. It includes loading and cleaning transactional and demographic data, performing exploratory data analysis (EDA), running SQL queries on a PostgreSQL server to aggregate and summarize data, and creating an interactive Power BI dashboard to visualize key metrics.

Format: CSV / Excel

Tools & Technologies

Python – Data loading, cleaning, and EDA (pandas, numpy, matplotlib, seaborn)

SQL – PostgreSQL for querying and aggregating data

Power BI – Dashboard creation and reporting

Jupyter Notebook – Code documentation and EDA presentation

Project Steps

1.Data Loading

Imported dataset using Python pandas

Verified data structure, columns, and types

2.Exploratory Data Analysis (EDA)

Checked for missing values, duplicates, and outliers

Visualized distributions, trends, and correlations

3.Data Cleaning

Handled missing values and inconsistent entries

Formatted columns and standardized data types

4.SQL Queries

Loaded cleaned data into PostgreSQL

Ran SQL queries to extract aggregated metrics, trends, and summaries

5.Dashboard & Reporting

Created an interactive Power BI dashboard with key metrics, charts, and filters

Generated a final report summarizing insights

Dashboard

The dashboard highlights:

Key performance metrics

Trends over time

Insights derived from SQL queries and EDA

Interactive filters for better analysis

Results

Identified key patterns and trends in the dataset

Summarized actionable insights through the dashboard

Created a reproducible workflow from raw data to final visualization

How to Run

Python Notebook

Open customer_shopping_behavior_analysis_checkpoint.ipynb in Jupyter Notebook or VS Code

Install dependencies:

pip install pandas numpy matplotlib seaborn

Run all cells to load, clean, and analyze the data

SQL Queries

Import the dataset into PostgreSQL

Run queries in your SQL client

Power BI Dashboard

Open customer_behavior_Dashboard.pbix in Power BI Desktop

Connect to dataset or SQL server as configured

Explore charts and filters

Notes

All scripts are reproducible and well-documented

Dataset can be replaced with similar structured data without changing workflow# customer_behavior_analysis
Data analytics project showcasing customer behavior analysis using python,SQL and  power BI.
