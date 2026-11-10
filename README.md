# 🧸 ToyJoy – Seasonal Inventory Management Analysis | Power BI
<img width="1343" height="741" alt="Screenshot (152)" src="https://github.com/user-attachments/assets/430e891e-4ef5-48d0-a6c1-65852b48e410" />
<img width="1380" height="704" alt="Screenshot (155)" src="https://github.com/user-attachments/assets/ca30d43a-4185-484f-ba16-7f223a696d47" />
<img width="1375" height="737" alt="Screenshot (154)" src="https://github.com/user-attachments/assets/6426aae3-e579-4767-9e79-f812599d0537" />


## 📌 Project Overview

ToyJoy is a retail toy company operating through multiple stores and online channels. The company faced inventory management challenges, including excess stock of certain products and frequent stockouts of high-demand products.

This project focuses on analyzing historical sales and inventory data to identify inventory inefficiencies, understand seasonal demand patterns, and provide actionable recommendations for better inventory planning.

Using **Power BI, DAX, and Data Analysis**, this project transforms raw inventory data into meaningful business insights through an interactive dashboard.

## 🎯 Business Objectives

- Identify products with excess inventory and low sales performance.
- Analyze products experiencing frequent stockouts.
- Understand seasonal demand patterns across different periods.
- Evaluate product and category-wise sales and revenue performance.
- Improve inventory turnover and stock availability.
- Recommend inventory optimization strategies to reduce costs and lost sales.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development and visualization |
| DAX | KPI calculations and business metrics |
| Power Query | Data cleaning and transformation |
| Microsoft Excel / CSV | Dataset preparation |
| Data Analysis | Exploratory analysis and business insights |

## 📊 Dataset Overview

The project uses a toy inventory dataset containing approximately **9,360 records** across **12 products** and **5 stores**.

The analysis covers approximately three years of historical data (2023–2025).

Key dataset attributes include:

- Product ID and Product Name
- Category
- Date
- Season
- Store ID
- Units Sold
- Inventory Levels
- Average Weekly Sales
- Weeks of Supply
- Inventory Status
- Revenue
- Cost of Goods Sold
- Stockout Observations
- Excess Inventory Value

## 📈 Key Performance Indicators (KPIs)

The following KPIs were developed using DAX in Power BI:

| KPI | Description |
|---|---|
| Total Revenue | Total revenue generated from product sales |
| Total Units Sold | Total quantity of products sold |
| Average Inventory | Average inventory level |
| Inventory Turnover Rate | Measures how efficiently inventory is converted into sales |
| Stockout Rate | Measures the frequency of inventory shortages |
| Excess Inventory Value | Estimates the cost of excess unsold inventory |
| Total Products | Number of distinct products |
| Total Records | Total number of dataset records |
| Weeks of Supply | Estimates how long available inventory can support demand |
| Seasonal Revenue | Revenue generated across different seasons |

## 📊 Power BI Dashboard

### 1. Seasonal Inventory Management Overview

Provides a high-level view of business performance.

Key visualizations:
- Total Revenue by Product
- Total Units Sold by Product
- Monthly Sales Trend
- Revenue by Category
- KPI Cards
- Interactive slicers for Category, Season, Store ID, and Date

### 2. Inventory & Stockout Analysis

Focuses on inventory availability and stock risk.

Key visualizations:
- Stockout Observations by Product
- Product-Level Inventory Analysis
- Average Inventory
- Total Units Sold
- Average Weekly Sales
- Weeks of Supply by Product and Store

### 3. Seasonal Demand Analysis

Analyzes product demand across different seasonal periods.

Key visualizations:
- Total Units Sold by Season
- Total Revenue by Season
- Product-wise Seasonal Sales Matrix
- Monthly Units Sold Trend

## 🔍 Key Business Insights

**1. Category Revenue Contribution**

- Board Games contribute the highest revenue of approximately 1.59M (37%).
- Dolls & Accessories contribute 0.96M (22.43%).
- Action Figures contribute 0.91M (21.15%).
- Puzzles contribute 0.83M (19.42%).

**2. Seasonal Demand Analysis**

- Holiday Season records the highest sales volume with 60,301 units.
- Summer Vacation contributes 52,637 units.
- Regular Season contributes 50,545 units.
- Easter / Spring contributes 21,641 units.

Holiday Season and Summer Vacation together account for approximately 61% of total units sold.

**3. Product-Level Inventory Analysis**

- Shadow Ninja records the highest units sold at 17,495.
- Ultra Robo Warrior has the lowest displayed weeks of supply at 0.37.
- Quest for Kingdom has 0.39 weeks of supply.
- 3D Solar System Puzzle and Tycoon Strategy Game show comparatively high stockout observations.

**4. Inventory Risk**

The dashboard identifies stockout risk across all 12 products. Products with low weeks of supply require closer monitoring and replenishment planning.

## 💡 Business Recommendations

### Short-Term Recommendations
- Prioritize replenishment of high-demand products with low weeks of supply.
- Monitor stockout-prone products across individual stores.
- Transfer available stock between stores where necessary.
- Investigate products with frequent stockout observations.

### Long-Term Recommendations
- Implement seasonal demand forecasting.
- Establish dynamic reorder points based on demand and supplier lead times.
- Introduce ABC analysis to prioritize inventory management.
- Monitor slow-moving and excess inventory regularly.
- Optimize warehouse capacity through demand-based purchasing.



## 📌 Project Learnings

Through this project, I gained practical experience in:

- Data cleaning and transformation using Power Query.
- Creating calculated measures using DAX.
- Developing interactive Power BI dashboards.
- Analyzing inventory turnover and stockout patterns.
- Identifying seasonal sales trends.
- Translating data insights into business recommendations.
- Solving real-world inventory management problems through data analytics.

## 🚀 Conclusion

This project demonstrates how data analytics and Power BI can help businesses make informed inventory management decisions.

By analyzing product performance, inventory levels, stockout risks, and seasonal demand, ToyJoy can improve stock availability, optimize inventory investment, reduce unnecessary holding costs, and support better business planning.
