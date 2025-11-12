# 📊 Sales & Product Data Analysis Project (Python)

## 📌 Overview  
This project is a **Python-based data analysis** that combines multiple datasets — sales, products, and suppliers — into a unified master dataset to generate meaningful business insights.  
It explores **sales performance**, **product profitability**, and **supplier efficiency** through data cleaning, merging, and visualization using **Pandas**, **Seaborn**, and **Matplotlib**.

---

## ⚙️ Project Workflow

### 🧩 1. Importing Libraries
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

## 📂 2. Data Loading and Merging

The project uses four main datasets:

sales_part1.xls and sales_part2.xls → Sales data.

products.xls → Product information.

suppliers.xls → Supplier details.

All datasets are merged step-by-step into a unified DataFrame named master_df, which holds complete sales, product, and supplier details.
