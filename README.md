# 📊 Inventory Performance Analysis – Power BI Dashboard

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Key Objectives](#-key-objectives)
- [Dataset & Preparation](#-dataset--preparation)
- [PowerBI Implementation](#-powerbi-implementation)
- [Files in This Repository](#-files-in-this-repository)
- [Dashboard](#-dashboard)
- [How to Run the Dashboard](#-how-to-run-the-dashboard)
- [Key Insights & Findings](#-key-insights--finding)
- [Business Recommendations](#-business-recommendations)
- [Skills Demonstrated](#-skills-demonstrated)
- [Conclusion](#-conclusion)
- [Contact](#-contact)

---

## 📌 Project Overview

This project presents an end-to-end **Inventory Performance Analysis Dashboard** created using **Power BI**, aiming to provide actionable insights on inventory value, stock movement, demand patterns, and product classifications using data analytics and business intelligence.

The dashboard highlights stock efficiency, ABC classifications, supplier performance, and demand trends—helping stakeholders make better supply chain and purchasing decisions.

---

## 🎯 Key Objectives

- Analyze stock movement and overall inventory performance  
- Identify high-value and low-performing inventory  
- Evaluate supplier contributions  
- Categorize products using **ABC analysis**  
- Highlight stockouts, overstock, and dead stock  
- Provide business recommendations for optimization  

---


## 📂 Dataset & Preparation

**Dataset:** `Inventory-Records-Data.xlsx`  
**Rows:** ~5,000  
**Columns Include:** Product, Category, Supplier, Cost, Selling Price, Quantity, Date, Stock Level, Order Status, and more.

### ✔ Data Cleaning Steps  
- Removed duplicates and null values  
- Standardized date and category formats  
- Normalized text fields  
- Created new calculated fields  
- Verified consistency and outliers  

### ✔ DAX Measures Included  
- Total Inventory Value  
- Total Sales  
- Inventory Turnover  
- Days in Inventory  
- ABC Category Calculation  
- Dead Stock Flag  

---

## 🛠 PowerBI Implementation

The dashboard is composed of multiple analytical sections:

### ✔ Main KPI Cards  
- Total Stock Value  
- Total Products  
- Total Stockouts  
- Inventory Turnover  

### ✔ Visualizations  
- Column/Bar Charts  
- Donut Charts  
- Line Graphs  
- Matrices with Conditional Formatting  
- Slicers for Supplier, Category, Status  

---

## 📁 Files in This Repository

```
Inventory-Performance-Analysis/
├── Inventory-Performance-Dashboard.pbix              # PowerBI Dashboard
├── data/
│   └── Inventory-Records-Data.xlsx                   # Project Data
├── docs/
│   └── Inventory_Performance_Analysis_Report.pdf     # Project Report
├── screenshots/
│   └── Inventory-Records-Dashboard image.png         # Project dashboard image
└── README.md
```

---

## 📈 Dashboard

![image alt](https://github.com/risitsahoo/inventory-performance-analysis-dashboard-powerbi/blob/main/Inventory-Records-Dashboard%20image.png?raw=true)

---

## ▶ How to Run the Dashboard

1. Download the `.pbix` Power BI file  
2. Open it using **Power BI Desktop**  
3. Refresh the dataset if needed  
4. Explore visuals, filters, and drill-through insights  

---

## 📈 Key Insights & Findings

### 🔹 Inventory Efficiency  
- Many categories show **slow turnover**, increasing holding costs.  
- **A-category items** represent **75%+ of the inventory value** but only ~20% of the total items.

### 🔹 Demand Behavior  
- Demand fluctuates seasonally in certain months.  
- Numerous recurring **stockout events** suggest forecasting issues.

### 🔹 Supplier Analysis  
- A small number of suppliers drive most high-value items.  
- Some suppliers show inconsistent order fulfillment.

### 🔹 ABC Summary  
| Class | Contribution | Business Meaning |
|-------|--------------|------------------|
| A | 70–80% value | Critical items needing constant monitoring |
| B | ~15% value | Moderate importance, stable stock |
| C | 5–10% value | Low priority, high overstock risk |

---

## 💡 Business Recommendations

- Increase visibility and reorder frequency for A-class products  
- Lower procurement volume for C-class items  
- Strengthen supplier evaluation and negotiation  
- Use automated reorder alerts to reduce stockout frequency  
- Optimize safety stock based on demand forecasting  

---

## 📚 Skills Demonstrated

- Power BI (DAX, Data Modeling, Visual Design)  
- Data Cleaning & Transformation  
- Inventory & Supply Chain Analytics  
- Business Intelligence Storytelling  
- Insight Extraction & Reporting  
- Dashboard Documentation  

--- 

## 🧩 Conclusion

The Inventory Performance Dashboard provides a clear, business-focused understanding of stock efficiency, demand behavior, and supplier contribution.  
It demonstrates real-world data analytics skills and the ability to transform raw inventory data into measurable, actionable insights.

---

## 📬 Contact

**Risit Sahoo**  
📧 Email: risit.sahoo121@gmail.com  
🔗 LinkedIn: [linkedin.com/in/risitsahoo](https://linkedin.com/in/risitsahoo)
