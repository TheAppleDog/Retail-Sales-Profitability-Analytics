# Retail Sales & Profitability Analytics | Tableau

## 📌 Project Overview
This project explores retail sales and profitability using Tableau. The goal is to understand business performance across regions, product categories, and individual products, and to identify areas where sales growth may not translate into profit.

## 🎯 Business Questions
- How do sales and profit change over time?
- Which regions and categories contribute to sales and profitability?
- Which products generate the highest sales?
- Which products have the lowest profit or generate losses?
- How does discounting relate to profitability?

## 🛠️ Tools & Techniques
- Tableau
- Tableau Sample Superstore dataset
- Data visualization and dashboard design
- Calculated fields and KPI development
- Filters and interactive dashboard actions
- Profit margin and product profitability analysis

## 📊 Dashboards

### 1. Executive Overview
Provides a high-level view of retail performance through:
- Total Sales
- Total Profit
- Total Orders
- Profit Margin
- Monthly sales and profit trends
- Sales by region and category
- Top 10 products by sales

### 2. Profitability Deep Dive
Explores profitability drivers and potential risk areas through:
- Profit and profit margin KPIs
- Discount versus profit analysis
- Profitability by category and region
- Bottom 10 products by profit
- Loss-making product analysis
- Interactive dashboard filtering and selection

## 🧮 Key Calculations

**Profit Margin**
```text
SUM([Profit]) / SUM([Sales])
```

**Profit Status**
```text
IF [Profit] > 0 THEN "Profitable"
ELSEIF [Profit] < 0 THEN "Loss"
ELSE "Break Even"
END
```

**Loss-Making Product Count**
```text
COUNTD(
    IF [Profit] < 0 THEN [Product Name] END
)
```

## 💡 Business Value
The dashboards help users investigate where revenue is generated, where profit is lost, and which products or business segments may need further investigation.

## 📷 Dashboard Screenshots
Add screenshots of both completed dashboards here.

Suggested filenames:
- `executive-overview.png`
- `profitability-deep-dive.png`

## 📁 Dataset
Tableau Sample Superstore sample dataset. Include the specific source or download link you used if available.

## ⚠️ Limitations
The analysis describes patterns in the available dataset. Discount and profitability relationships should not automatically be interpreted as proof of causation.

## 👩‍💻 Project Type
Self-directed Data Analytics portfolio project.

## 🏷️ Skills
Tableau · Data Visualization · Dashboard Design · KPI Analysis · Calculated Fields · Business Analysis
