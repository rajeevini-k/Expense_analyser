# Expense_analyser
A Python project that cleans and analyzes a messy expense dataset using Pandas and NumPy. It handles missing and invalid data, performs feature engineering, and generates insights on spending patterns by category, payment mode, and time trends, supported with clear Matplotlib visualizations and robust conditional analysis.
# Expense Data Cleaning & Analysis Project

A Python-based data analysis project that cleans, processes, and analyzes a messy expense dataset to extract meaningful financial insights.

---

## Project Overview

This project demonstrates a complete data analysis workflow:
- Data cleaning (handling missing, invalid, and inconsistent values)
- Feature engineering (time-based features)
- Exploratory Data Analysis (EDA)
- Data visualization
- Insight generation

It is designed to simulate real-world financial data analysis.

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib

---

## Dataset Features

The dataset includes:
- Date of transaction
- Amount spent
- Category of expense
- Payment mode


## Workflow

### 1. Data Cleaning
- Converted invalid dates to NaT
- Handled non-numeric and negative amounts
- Fixed missing/blank category and payment mode values

### 2. Feature Engineering
- Extracted Month, Year, Day Name
- Identified Weekends
- Created Weekly grouping

### 3. Analysis Performed
- Total & average spending
- Category-wise spending
- Payment mode distribution
- Weekly spending trends
- Weekend vs weekday comparison

> Monthly analysis is applied only if multiple months exist in the dataset.



## Visualizations

- Category-wise spending (Bar Chart)
- Payment mode distribution (Pie Chart)
- Weekend vs Weekday spending
- Weekly spending trend
- Monthly trend (conditional)


## Key Insights

- Identifies top spending categories
- Shows most used payment methods
- Highlights spending patterns over time
- Detects weekend vs weekday behavior
- Handles real-world messy data robustly


## How to Run

```bash
pip install pandas numpy matplotlib
python expense_analysis.py
