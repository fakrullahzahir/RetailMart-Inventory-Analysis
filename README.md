# RetailMart Inventory Analysis

## Project Overview

This project analyzes inventory data for a fictional retail company, **RetailMart Malaysia**, to identify inventory shortages, reorder risks, and warehouse performance.

The analysis follows a real-world data analytics workflow, including data cleaning, exploratory data analysis (EDA), business insights, and recommendations for inventory management.

<img width="854" height="552" alt="distribution_curr_stock" src="https://github.com/user-attachments/assets/97b6406d-0d63-459c-903c-c2842feaa895" />
<img width="854" height="601" alt="reorder_risk_warehouse" src="https://github.com/user-attachments/assets/e79cd889-81ac-4504-9eda-34950c6837b7" />
<img width="880" height="601" alt="total_current_stock_warehouses" src="https://github.com/user-attachments/assets/b30e988d-7049-4bf9-a4ae-57104356bd3c" />
<img width="989" height="590" alt="top10_replenishment_products" src="https://github.com/user-attachments/assets/afa37234-42da-43fc-96ac-eba43016d158" />

---

## Business Problem

RetailMart has experienced increasing inventory shortages across multiple warehouses.

Management would like to understand:

- Which warehouses store the most inventory?
- Which products require immediate replenishment?
- Which product categories contribute the most to inventory shortages?
- Which products should be prioritised for reorder?

---

## Dataset

The project uses a simulated retail inventory database consisting of multiple related datasets.

| Dataset | Description |
|----------|-------------|
| inventory.csv | Inventory records across warehouses |
| products.csv | Product master data |
| suppliers.csv | Supplier information |
| warehouses.csv | Warehouse information |
| purchase_orders.csv | Purchase order records |
| sales.csv | Sales transactions |

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- VS Code

---

## Project Workflow

1. Business Understanding
2. Data Import
3. Data Cleaning
4. Data Validation
5. Exploratory Data Analysis (EDA)
6. Business Insights
7. Business Recommendations

---

## Key Analyses

### Inventory Overview

- Total inventory records
- Warehouse inventory distribution
- Inventory summary statistics

### Reorder Analysis

- Products below reorder level
- Top 10 products requiring immediate replenishment
- Warehouse reorder risk
- Category reorder analysis
- Total vs Average Reorder Gap

---

## Key Findings

- 10,000 inventory records analysed
- 1,000 unique products
- 768 inventory records require replenishment
- 533 unique SKUs fall below the reorder level
- KK warehouse stores the highest inventory volume
- Home category has the highest total reorder gap
- Pet category has the highest average reorder gap

---

## Recommendations

- Prioritise products with the highest Reorder Gap.
- Review warehouse replenishment strategies.
- Monitor categories with high average shortages.
- Implement automated inventory alerts.
- Review inventory planning on a regular basis.

---

## Repository Structure

```
RetailMart-Inventory-Analysis/

├── data/
├── notebooks/
├── images/
├── README.md
└── requirements.txt
```

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Validation
- Business Analysis
- Feature Engineering
- Data Visualization
- Business Communication
- Inventory Analytics

---

## Author

**Muhammad Fakrullah**

Bachelor of Computer Science

Aspiring Data Analyst

GitHub: https://github.com/fakrullahzahir
