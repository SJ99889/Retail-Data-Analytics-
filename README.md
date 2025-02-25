Quantium Retail Data Analytics

Overview

This project involves analyzing retail transaction data for Quantium to derive insights into customer purchasing behaviors, sales trends, and the impact of various retail experiments. The project is divided into two tasks:

Task 1: Data cleaning, preprocessing, and exploratory data analysis (EDA) on customer transaction data.

Task 2: A/B testing and experimental design to assess the impact of trial stores on sales.

Task 1: Data Preprocessing & Exploratory Data Analysis (EDA)

Steps:

Data Loading: Imported transaction data (QVI_purchase_behaviour.csv & QVI_transaction_data.xlsx).

Data Cleaning:

Checked for missing and duplicate values.

Corrected data types.

Created new columns such as Packet_Size and Brand.

Removed unwanted rows (e.g., non-chip products like Salsa).

Standardized brand names.

Identified and removed outliers.

EDA:

Analyzed the distribution of life stages and premium customer segments.

Identified the most popular chip brands and purchasing trends.

Merged transaction data with customer demographics for deeper insights.

Examined monthly and seasonal sales patterns.

Task 2: Experimentation & Impact Analysis

Goal:

Evaluate the impact of a trial on retail stores by selecting appropriate control stores and analyzing pre-trial and post-trial sales performance.

Steps:

Store Selection:

Identified trial stores (Store 77, 86, 88).

Selected control stores based on similarity in total sales, customer count, and transaction patterns.

Control Store Matching:

Used correlation and magnitude distance metrics to find the best-matching control stores.

Computed composite similarity scores to rank control stores.

Trial Impact Assessment:

Compared sales trends before and after the trial period.

Performed statistical tests to determine significant differences in sales performance.

Created visualizations to compare trial and control store sales and customer counts over time.

Assessed whether the trial led to a statistically significant uplift in sales.
