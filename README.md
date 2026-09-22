# Store 1 — Customer Data Cleaning & Segmentation

A data cleaning and segmentation project using Python to prepare a customer database for a loyalty program launch.

---

## Overview

Store 1 needed its raw customer data cleaned and structured before running any marketing campaign. This project transforms inconsistent records into an analysis-ready dataset and answers three key business questions using Python's core data structures.

## Business Questions Answered

- What is the total revenue generated across all customers?
- Which young customers (under 30) represent high-value segments?
- Which customers can be targeted by product category?

## Key Findings

| Metric | Result |
|---|---|
| Total customers | 10 |
| Total revenue | $9,189 |
| Customers under 30 | 5 |
| High-value customers under 30 (>$1,000) | 2 |
| Customers in 'home' category | 5 |

## What the Code Does

- **Data cleaning pipeline** — normalizes names, converts data types, and standardizes categories
- **Revenue calculation** — uses generator expressions for memory-efficient aggregation
- **Customer segmentation** — filters by age, spending threshold, and product category
- **Reusable function** — `get_clients_by_category()` enables flexible targeting without duplicating logic

## Tech Stack

- Python 3
- Jupyter Notebook
- No external libraries — core Python only

## Project Structure

```
store1-customer-analysis/
│
├── store1_customer_analysis.ipynb   # Main analysis notebook
└── README.md
```

## About

Built as part of the TripleTen Data Science program.  
Author: Mario Noriega
