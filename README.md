
# RFM Analysis for ABC Superstore

This project performs an RFM (Recency, Frequency, Monetary) analysis on sales data from ABC Superstore to segment customers based on their purchasing behavior.

## Overview

RFM analysis is a marketing technique used to quantitatively rank and group customers based on:

- **Recency**: How recently a customer made a purchase
- **Frequency**: How often they purchase
- **Monetary**: How much money they spend

## Objectives

- Understand the customer purchase behavior through data exploration.
- Calculate RFM values for each customer.
- Score customers on each RFM metric.
- Segment customers based on their RFM scores.

## Dataset

- File: `Sample - Superstore.xlsx`
- Data contains order details including `Customer ID`, `Order Date`, `Sales`, and `Order ID`.

## Steps in the Notebook

1. Load and explore the data
2. Process dates and filter relevant columns
3. Calculate RFM values:
    - Recency: Days since last purchase
    - Frequency: Number of purchases
    - Monetary: Total amount spent
4. Score customers on a scale of 1 to 5 for each RFM metric
5. Combine scores into an RFM score and assign customer segments

## Customer Segments

Example rule-based segmentation includes:
- **Champion**: Recent and frequent buyers
- **Loyal**: Regular purchasers
- **Recent**: New, recent buyers
- **Frequent**: Often purchasing but not recent
- **Others**: Less engaged customers

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- openpyxl (for reading .xlsx files)

## How to Run

1. Open the Jupyter Notebook: `RFM_Analysis_ABC_Superstore.ipynb`
2. Execute each cell in order
3. Review the final customer segmentation output
