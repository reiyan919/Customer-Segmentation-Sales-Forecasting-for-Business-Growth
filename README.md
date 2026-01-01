Global Superstore Sales Analysis & Business Insights (2014–2017)

🔹 Project Overview

This project analyzes sales data from a global retail superstore to uncover business insights, regional performance patterns, and category-level differences using statistical analysis and data visualization.

The goal is to demonstrate an end-to-end data analytics workflow:

data cleaning

exploratory data analysis (EDA)

hypothesis testing

business interpretation

dashboard design

🔹 Dataset Description

The dataset represents retail transactions over four years (2014–2017) and includes information on:

orders and shipment dates

customer and geographic details

product categories and sub-categories

sales values

Source (Reputable & Widely Used):
Kaggle – Global Superstore / Sales Forecasting Dataset
https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

This dataset is commonly used in Tableau, Power BI, and analytics training.

🔹 Tools & Technologies

Python (pandas, scipy, statsmodels, matplotlib)

Tableau (dashboard & visual analytics)

Statistical methods (Chi-square, ANOVA, Tukey HSD)

🔹 Data Cleaning & Preparation

Steps performed:

Converted Order Date and Ship Date to datetime format

Handled missing values in Postal Code using mode

Checked for duplicates and data consistency

Verified sales values (no negative sales detected)

Reference (Best Practices):
IBM – Data Preparation & Cleaning
https://www.ibm.com/topics/data-cleaning

🔹 Exploratory Data Analysis (EDA)

Key analyses:

Sales distribution and descriptive statistics

Sales trends over time

Category and sub-category contribution

Regional and city-level sales concentration

EDA helps identify patterns and anomalies before modeling.

Reference:
Google – Exploratory Data Analysis Guide
https://developers.google.com/machine-learning/guides/good-data-analysis

🔹 Statistical Analysis
1️⃣ Chi-Square Test of Independence

Objective:
To examine whether Sales Category (Low / Medium / High) is associated with Region.

Test used: Chi-square test

Result: Statistically significant association (p < 0.05)

Interpretation: Sales distribution differs by region

Reference:
Khan Academy – Chi-Square Test
https://www.khanacademy.org/math/statistics-probability

2️⃣ ANOVA & Post-Hoc Analysis

Objective:
To compare mean sales across product categories.

One-way ANOVA showed significant differences

Tukey HSD confirmed all category pairs differ significantly

References:
UCLA Stats – ANOVA & Tukey HSD
https://stats.oarc.ucla.edu/

🔹 Dashboard (Tableau)

The interactive dashboard includes:

KPI cards (Total Sales, Average Sales, Number of Orders)

Sales trends over time

Category × Region performance table

Top customers by sales

Geographic sales map

Design Principles Reference:
Tableau – Dashboard Design Best Practices
(https://public.tableau.com/app/profile/rayan.ra4401/viz/GlobalSuperstoreSalesPerformance_17672117692100/Dashboard1)
🔹 Key Business Insights

Sales performance varies significantly by region

Technology category generates the highest average sales

A small group of customers contributes disproportionately to revenue

Sales show a clear upward trend over time

🔹 Conclusion

This project demonstrates how data analytics and statistics can support business decision-making by identifying performance gaps, regional differences, and high-value customers.
