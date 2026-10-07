# 📊 Superstore Data Visualization & Business Analysis

> A data visualization project using Python to analyze sales,
> profitability, products, customers, regions, and discount impact.

---

## 📌 Project Overview

This project focuses on analyzing and visualizing business performance
using the Superstore dataset.

The objective is to transform raw sales data into meaningful
visualizations and business insights that can support data-driven
decision-making.

The analysis covers sales trends, profitability, product performance,
customer segments, regional performance, discount impact, and
relationships between key business metrics.

---

## 🎯 Objectives

- Analyze overall sales and profit performance
- Identify sales and profit trends over time
- Compare product categories and sub-categories
- Analyze regional and customer segment performance
- Understand the relationship between discounts and profitability
- Calculate profit margins
- Identify the most profitable products
- Generate actionable business insights

---

## 🛠️ Technologies & Tools

- **Python**
- **Pandas** — Data manipulation and analysis
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Analysis environment
- **Excel (.xls)** — Source dataset
- **Git & GitHub** — Version control and project hosting

---

## 📂 Project Structure

```text
CodeAlpha_Task3_Data_Visualization/
│
├── data/
│   └── sample_-_superstore.xls
│
├── notebooks/
│   └── data_visualization.ipynb
│
├── outputs/
│   ├── charts/
│   │   ├── monthly_sales_trend.png
│   │   ├── monthly_profit_trend.png
│   │   ├── sales_by_category.png
│   │   ├── profit_by_category.png
│   │   ├── sales_vs_profit_category.png
│   │   ├── top_10_subcategories_sales.png
│   │   ├── top_10_subcategories_profit.png
│   │   ├── regional_sales_profit.png
│   │   ├── sales_by_segment.png
│   │   ├── yearly_sales_profit.png
│   │   ├── discount_vs_profit.png
│   │   ├── profit_margin_category.png
│   │   ├── correlation_heatmap.png
│   │   ├── sales_vs_profit.png
│   │   ├── top_10_profitable_products.png
│   │   └── business_performance_kpis.png
│   │
│   └── insights/
│       └── business_insights.md
│
├── src/
│   ├── data_loader.py
│   ├── preprocessing.py
│   └── visualizations.py
│
├── requirements.txt
├── .gitignore
└── README.md
---

## 📊 Key Performance Metrics

| Metric | Value |
|---|---:|
| Total Sales | $2,326,534.35 |
| Total Profit | $292,296.81 |
| Total Orders | 5,111 |
| Total Customers | 804 |
| Overall Profit Margin | 12.56% |

---

## 🔎 Key Business Insights

### 🥇 Technology Leads Overall Performance

Technology generated the highest sales and profit among the major
product categories.

- Sales: **$839,893.28**
- Profit: **$146,543.38**
- Profit Margin: **17.45%**

### ⚠️ Furniture Has Low Profitability

Furniture generated **$754,747.76** in sales but only
**$19,730.00** in profit.

Its profit margin is just **2.61%**, indicating that high sales
volume does not necessarily result in strong profitability.

### 🌎 West Is the Strongest Region

The West region generated the highest sales and profit.

- Sales: **$739,813.61**
- Profit: **$110,798.82**

### 👥 Consumer Segment Leads Sales

The Consumer segment generated the highest sales at
**$1,170,659.79**.

### 📦 Sales Leaders and Profit Leaders Differ

Chairs generated the highest sub-category sales at
**$335,768.25**, while Copiers generated the highest profit at
**$56,093.94**.

This demonstrates why sales volume alone is not enough to evaluate
product performance.

### 🏷️ High Discounts Reduce Profitability

The analysis shows substantial losses at higher discount levels.

- 60% discount → **-$6,164.35 profit**
- 70% discount → **-$40,300.57 profit**
- 80% discount → **-$30,565.27 profit**

---

## 📈 Visualizations

The project includes visualizations covering:

- Monthly Sales Trend
- Monthly Profit Trend
- Sales by Category
- Profit by Category
- Sales vs Profit by Category
- Top 10 Sub-Categories by Sales
- Top 10 Sub-Categories by Profit
- Regional Sales vs Profit
- Sales Distribution by Customer Segment
- Yearly Sales & Profit Performance
- Discount vs Profit
- Profit Margin by Category
- Correlation Heatmap
- Sales vs Profit Relationship
- Top 10 Most Profitable Products
- Business Performance KPI Overview

All generated charts are available in:

`outputs/charts/`

---

## 💡 Business Recommendations

1. Review pricing and cost structures within the Furniture category.
2. Control aggressive discounting to protect profit margins.
3. Focus on high-profit products such as Copiers.
4. Study successful strategies in the West region.
5. Continue strengthening the Technology category due to its strong
   sales and profitability.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>

```<bash>

cd CodeAlpha_Task3_Data_Visualization

```<bash>

pip install -r requirements.txt

`<bash>

notebooks/data_visualization.ipynb
Run the notebook from top to bottom.

📚 Dataset

The project uses the Superstore dataset containing information about
orders, customers, products, sales, discounts, and profits.

The dataset is used for educational and analytical purposes.

👨‍💻 Author

Srinu

Computer Science / Artificial Intelligence & Data Science Student

Interested in Data Analytics, Python, SQL, and solving real-world
business problems using data.

⭐ Project Outcome

This project demonstrates an end-to-end data visualization workflow:

Raw Data → Data Preparation → Analysis → Visualization → Business Insights → Recommendations

### One important thing

Leave this:

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>