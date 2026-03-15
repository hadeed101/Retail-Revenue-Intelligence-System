# 🛒 Retail Revenue Intelligence System

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green?style=flat&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-1.24-orange?style=flat&logo=numpy)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat)

> **Exploratory Data Analysis (EDA)** on a retail sales dataset to uncover revenue trends,
> top-performing products, regional performance, and category-wise profitability.
> Analyzed **500 orders** across **4 regions** and **4 categories** using Python & Pandas.

---

## 📁 Project Structure

```
Retail-Revenue-Intelligence/
│
├── project 001.csv                      # Raw sales dataset (500 orders)
├── Retail_Revenue_Intelligence.ipynb    # Main analysis notebook
└── README.md                            # Project documentation
```

---

## 📊 Dataset Overview

| Feature | Details |
|---------|---------|
| 📦 Total Orders | 500 |
| 🗓️ Time Period | Jan 2023 – Dec 2023 |
| 🌍 Regions | North, South, East, West |
| 📦 Categories | Electronics, Clothing, Sports, Home |
| 💰 Total Revenue | $765,955.08 |

### Columns

| Column | Description |
|--------|-------------|
| `order_id` | Unique order identifier |
| `order_date` | Date of order |
| `region` | Sales region (North/South/East/West) |
| `category` | Product category |
| `product` | Product name |
| `quantity` | Number of units sold |
| `price` | Unit price |
| `Total Revenue` | Calculated column — quantity × price |

---

## 🔍 Analysis Performed

### ➕ Feature Engineering
- Created new `Total Revenue` column → `quantity × price`

### 🌍 Regional Performance
- Compared revenue across all 4 regions
- **North** region leads with **$199,679**
- **East** region needs attention — lowest revenue at **$174,784**

### 🏆 Product Ranking
- Top 5 products by Total Revenue
- **Smartphone** is #1 revenue generator at **$69,704**
- Followed by Tennis Racket, Gym Gloves, Lamp, Mixer

### 📦 Category Analysis
- Revenue breakdown by product category
- **Sports** is most profitable → **$228,378**
- **Clothing** is least profitable → **$149,675**

### 📅 Time Analysis
- Monthly revenue trend for full year 2023
- **August** is peak sales month → **$82,225**
- **July** is slowest month → **$45,777**

---

## 💡 Key Insights

| # | Insight | Finding |
|---|---------|---------|
| 1 | 🥇 Best Region | **North** — highest revenue ($199,679) |
| 2 | ⚠️ Weakest Region | **East** — needs strategic focus |
| 3 | 🏆 Top Product | **Smartphone** — #1 revenue generator |
| 4 | 📦 Best Category | **Sports** — most profitable |
| 5 | 📉 Weakest Category | **Clothing** — lowest revenue |
| 6 | 📅 Peak Month | **August** — highest sales |
| 7 | 📉 Slowest Month | **July** — lowest sales |

---

## 🛠️ Tools & Libraries

```python
import pandas as pd    # Data manipulation & analysis
import numpy as np     # Numerical operations
```

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/yourusername/Retail-Revenue-Intelligence.git
cd Retail-Revenue-Intelligence
```

2. Install dependencies
```bash
pip install pandas numpy jupyter
```

3. Launch Jupyter Notebook
```bash
jupyter notebook Retail_Revenue_Intelligence.ipynb
```

---

## 👨‍💻 Author

**Hadeed Malik**
📧 hadeedmalik504@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/hadeed-malik-28b11731b)) | [GitHub](https://github.com/hadeed101)

---

*This project was built for Data Analysis practice — focused on retail sales intelligence using Python & Pandas.*
