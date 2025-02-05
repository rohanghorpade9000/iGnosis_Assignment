# iGnosis_Assignment

Overview

This project analyzes customer purchase behavior using transaction and customer demographic data. The goal is to identify spending patterns, customer segmentation, and product popularity to optimize marketing strategies and promotions.

Data Sources

purchase_behaviour.csv: Contains customer demographic information, including life stage and premium status.
transaction_data.csv: Contains details of customer transactions, including product name, sales amount, and quantity purchased.

Key Analysis Steps

1. Data Loading & Cleaning
The data is loaded into pandas DataFrames.
Missing values are checked and handled appropriately.

2. Customer Segmentation

The distribution of customers by life stage (LIFESTAGE) is visualized.
The distribution of customers by premium category (PREMIUM_CUSTOMER) is analyzed.
A combined analysis of LIFESTAGE and PREMIUM_CUSTOMER is performed.

3. Product Performance Analysis

The top 3 most profitable products are identified based on total sales (TOT_SALES).
The top 3 best-selling products are determined based on quantity sold (PROD_QTY).

4. Customer Loyalty Analysis

Customers are ranked based on their total spending (TOT_SALES).
The most frequent customer groups are identified based on total purchases.
The characteristics of the highest-spending customers are analyzed.

5. Average Spend Analysis

The average spend per customer segment (LIFESTAGE, PREMIUM_CUSTOMER) is calculated.
The average spend per transaction per customer (LYLTY_CARD_NBR) is computed and summarized.

Dependencies

Python 3.x
Pandas
NumPy
Matplotlib
Seaborn

How to Run

Install required dependencies using:
pip install pandas numpy matplotlib seaborn
Ensure purchase_behaviour.csv and transaction_data.csv are in the working directory.
Run the script to generate insights and visualizations.
