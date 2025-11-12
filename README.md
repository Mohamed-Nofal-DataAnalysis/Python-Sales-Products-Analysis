# 📊 Sales & Product Data Analysis Project (Python)
## 📌 Overview

This project is a Python-based data analysis that combines multiple datasets — sales, products, and suppliers — into a unified master dataset to generate meaningful business insights.
It explores sales performance, product profitability, and supplier efficiency through data cleaning, merging, and visualization using Pandas, Seaborn, and Matplotlib.
## Dataset Used
[Download Full Dataset ](https://github.com/Mohamed-Nofal-DataAnalysis/Python-Sales-Products-Analysis/tree/main/Dataset)
## ⚙️ Project Workflow
## 🧩 1. Importing Libraries
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
## 📂 2. Data Loading and Merging

The project uses four main datasets:

sales_part1.xls and sales_part2.xls → Sales data

products.xls → Product information

suppliers.xls → Supplier details

All datasets are merged step-by-step into a unified DataFrame named master_df, which holds complete sales, product, and supplier details.

## 🧹 3. Data Cleaning & Exploration

Performed data integrity checks:

Data types (dtypes)

Missing values (NaN)

Duplicates

Descriptive statistics for numerical and categorical columns

## 💰 4. Derived Metrics

Created new financial columns to support analysis :\
```python
master_df["revenue"] = master_df["quantity"] * master_df["sale_price"]
master_df["profit"] = master_df["sale_price"] - master_df["cost_price"]
```
## 📈 5. Visualization & Insights

Analytical visualizations were built using Seaborn and Matplotlib :

Profit distribution per product and supplier

Top-selling products

Supplier performance comparison

Pricing trends and patterns

🧮 Libraries Used
Library	Purpose
pandas	Data loading, cleaning, manipulation
numpy	Mathematical operations
matplotlib	Basic plotting
seaborn	Advanced analytical visualization
## 🧰 How to Run

1- Create a virtual environment :
```python
python -m venv .venv
source .venv/bin/activate   # Linux/Mac  
.venv\\Scripts\\activate    # Windows
```
2-Install requirements :
```python
pip install -r requirements.txt
```
3- Run the notebook :
```python
jupyter notebook Task..ipynb
```
🧾 Requirements
```python
pandas
numpy
matplotlib
seaborn
```
## Dashboard Screenshots (Click to enlarge) :
<img src="https://github.com/Mohamed-Nofal-DataAnalysis/Python-Sales-Products-Analysis/blob/main/Total%20Revenue%20by%20Category.png">
<img src="https://github.com/Mohamed-Nofal-DataAnalysis/Python-Sales-Products-Analysis/blob/main/Total%20Revenue%20by%20Supplier.png">
<img src="https://github.com/Mohamed-Nofal-DataAnalysis/Python-Sales-Products-Analysis/blob/main/Total%20Revenue%20by%20Month.png">
<img src="https://github.com/Mohamed-Nofal-DataAnalysis/Python-Sales-Products-Analysis/blob/main/Quantity%20Distribution%20with%20Outliers.png">
<img src="https://github.com/Mohamed-Nofal-DataAnalysis/Python-Sales-Products-Analysis/blob/main/Quantity%20Distribution%20without%20Outliers.png">

📊 Expected Outputs

A complete sales performance report

Product-level profit summary

Supplier and pricing visualizations

Clear business insights and recommendations

🚀 Future Improvements

Add time-series analysis to track sales trends

Implement predictive modeling for demand forecasting

Build an interactive dashboard using Power BI or Plotly Dash

📜 License

MIT License — Open for educational and analytical purposes.
