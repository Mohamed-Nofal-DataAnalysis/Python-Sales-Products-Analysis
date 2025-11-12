📌 Overview

This project is a Python-based data analysis that combines multiple datasets — sales, products, and suppliers — into a unified master dataset to generate meaningful business insights.
It explores sales performance, product profitability, and supplier efficiency through data cleaning, merging, and visualization using Pandas, Seaborn, and Matplotlib.

⚙️ Project Workflow
🧩 1. Importing Libraries

The project uses Python’s main data analysis libraries such as Pandas, Numpy, Matplotlib, and Seaborn.

📂 2. Data Loading and Merging

The project uses four main datasets:

sales_part1.xls and sales_part2.xls → Sales data

products.xls → Product information

suppliers.xls → Supplier details

All datasets are merged step-by-step into a unified DataFrame named master_df, which holds complete sales, product, and supplier details.

🧹 3. Data Cleaning & Exploration

Performed data integrity checks:
```python
Data types (dtypes)

Missing values (NaN)

Duplicates

Descriptive statistics for numerical and categorical columns

💰 4. Derived Metrics

Created new financial columns to support analysis such as revenue and profit based on sales and cost prices.

📈 5. Visualization & Insights

Analytical visualizations were built using Seaborn and Matplotlib:

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
🧰 How to Run

Create a virtual environment:
python -m venv .venv
then activate it

Install requirements:
pip install -r requirements.txt

Run the notebook:
jupyter notebook Task..ipynb

🧾 Requirements

pandas
numpy
matplotlib
seaborn

📊 Expected Outputs

Complete sales performance report

Product-level profit summary

Supplier and pricing visualizations

Clear business insights and recommendations

🚀 Future Improvements

Add time-series analysis to track sales trends

Implement predictive modeling for demand forecasting

Build an interactive dashboard using Power BI or Plotly Dash

📜 License

MIT License — Open for educational and analytical purposes.
