
# ☕ Coffee Shop Sales Analysis

## 📌 Project Overview

This project presents an exploratory data analysis
(EDA) of coffee shop sales using Python.

The objective is to evaluate sales performance,
identify purchasing patterns, understand revenue
drivers, and provide actionable business recommendations.

## 🛠️ Technologies & Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

## 📊 Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Orders | 970 |
| Total Revenue | 12,558 AZN |
| Average Order Value | 12.95 AZN |
| Card Payment Share | 65.77% |
| Highest Revenue Product | Mocha |
| Best-Selling Product by Quantity | Latte |

## 🔍 Analysis Scope

- Data quality assessment
- Key performance indicators
- Product performance analysis
- Payment method analysis
- Order quantity and revenue distribution
- Weekday and weekend sales analysis
- Correlation analysis
- Multivariate analysis
- Order segmentation

## 💡 Key Business Insights

- Mocha generates the highest sales revenue.
- Latte is the best-selling product by quantity.
- Card payments are the preferred payment method.
- Cash payments have a slightly higher average order value.
- Product prices and order quantities influence revenue.

### Weekday vs Weekend Performance

| Metric | Weekday | Weekend |
|---|---:|---:|
| Orders | 629 | 235 |
| Revenue (AZN) | 8,149.50 | 3,018.00 |

An additional 106 orders without valid dates,
representing 1,390.50 AZN in revenue, were excluded
from date-based analysis but retained in overall metrics.

Aggregate weekday and weekend revenue should not
be interpreted as average daily performance.

## 📈 Business Recommendations

- Promote lower-selling products through targeted offers.
- Introduce product bundles to increase order value.
- Maintain convenient card payment options.
- Optimize inventory based on product demand.
- Plan staffing based on observed sales patterns.
- Test targeted promotions before full implementation.

## ⚠️ Data Quality & Limitations

- 106 orders contain missing or invalid dates.
- 21 orders contain missing product names.
- 65 records contain inconsistencies between recorded
  revenue and Quantity × Price.
- Recorded revenue values were retained because
  underlying transaction details were unavailable.
- Customer names were removed for privacy.
- Historical sales patterns do not guarantee
  future customer behavior.

## 📂 Project Structure

- `coffee_shop_eda.ipynb` — Main analysis notebook
- `coffee_shop_final.csv` — Dataset
- `requirements.txt` — Python dependencies
- `README.md` — Project documentation

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/sholamammadova/coffee-shop-sales-analysis.git
cd coffee-shop-sales-analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open `coffee_shop_eda.ipynb` using Jupyter Notebook
or JupyterLab and run all cells sequentially.

## 👩‍💻 Author

**Shola Mammadova**

Data Analyst | Python | SQL | Power BI | Excel

[GitHub Profile](https://github.com/sholamammadova)

