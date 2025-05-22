**Power-BI-Portfolio**
Here’s a well-structured **portfolio project description** for your **Coffee Shop Sales Dashboard** built in Power BI:

---

### 1)📝 **Project Title:**

**Coffee Shop Sales Insights Dashboard**

---

### 🎯 **Objective:**

To analyze and monitor coffee shop sales performance, product-wise sales contribution, peak sales hours, and regional store performance to support business decisions through data visualization.

---

### 🔑 **Key Features:**

* Interactive date filtering for **monthly sales analysis**
* Weekday vs Weekend sales breakdown
* Product category and item-level performance tracking
* Store-wise performance comparison with growth trends
* Hourly sales distribution across days
* Dynamic KPIs and trend analysis

---

### 📊 **Visualizations Used:**

* **KPI Cards** for Total Sales, Orders, Quantity Sold
* **Line and Bar Combo Charts** for Sales Trends
* **Donut Chart** for Weekday vs Weekend Analysis
* **Stacked Bar Charts** for Hourly Sales by Day
* **Horizontal Bar Charts** for Store and Product-level Sales

---

### 📐 **DAX Measures Used:**

* `Total Sales = SUM(Sales[Sales Amount])`
* `Total Orders = SUM(Sales[Order Quantity])`
* `Total Quantity Sold = SUM(Sales[Quantity])`
* `Sales Growth vs LM = DIVIDE([Current Month Sales] - [Last Month Sales], [Last Month Sales])`
* `Average Sales Per Day = AVERAGEX(VALUES('Calendar'[Date]), [Total Sales])`
* `Weekday/Weekend Sales Split using SWITCH and WEEKDAY logic`

---

### 📌 **KPIs Used:**

* **Total Sales**
* **Total Orders**
* **Total Quantity Sold**
* **% Growth vs Last Month**
* **Average Daily Sales**

---
**DASHBOARD IMAGES:**![COFFEE SHOP DASHBOARD](https://github.com/user-attachments/assets/2b65293b-2cf1-4ce8-87be-a26598c65d17)



**2) 📊 Finance Power BI Dashboard**

This interactive Finance Dashboard was developed to provide an overview of financial performance, enabling strategic decision-making with dynamic filters and user-friendly visuals.

---

**✅ Objectives:**
- Monitor financial KPIs and cash flow trends.
- Identify performance gaps across financial categories and time periods.
- Drill-down into expenses and revenues for deeper insights.

---

**📌 Key Features:**
- **Dynamic Date Filters** for custom date ranges.
- **Category Breakdown** of income and expenses.
- **Visuals** like bar charts, line graphs, Treemaps, and KPI cards.

---

**📊 Visualizations Used:**
- **KPI Cards** for Total Income, Expenses, and Profit Margin.
- **Line & Column Charts** for monthly trends and category breakdowns.
- **Treemaps** for quick visual of spending proportions.

---

**🧮 DAX Measures:**
- **Monthly Average:** `AVERAGEX` over months.
- **Cumulative Totals:** `TOTALYTD` for running sums.
- **Profit Margin:** `(Total Income - Total Expenses) / Total Income`.
- **Variance Analysis:** Comparison of current vs. previous periods.

---

**📈 KPIs Included:**
- **Total Income & Expenses**
- **Net Profit** (Income - Expenses)
- **Profit Margin (%):** Measures profitability.
- **Cumulative Totals** to track growth over time.
- **Highest Expense Category** to assist in cost control.

---

**⚙️ Tools & Technologies Used:**
- [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/)
- [DAX](https://docs.microsoft.com/en-us/dax/)
- [Power Query Editor](https://docs.microsoft.com/en-us/power-query/)

---



Dashboard Url: https://app.powerbi.com/view?r=eyJrIjoiNTg3NWJkNzktNzQxNy00NDNkLTllNTAtYTY2ZDEzYmQ0ZTI3IiwidCI6IjhhMzhkNWM5LWZmMmYtNDc5ZS04NjM3LWQ3M2Y2MjQxYTRmMCIsImMiOjEwfQ%3D%3D

**DASHBOARD IMAGES:**

![6078100278801974883 (2)](https://github.com/user-attachments/assets/37488f32-3795-4cc1-8bdf-579c8dec5f52)
![6078100278801974056 (2)](https://github.com/user-attachments/assets/d5f382e0-fa30-4dbf-b2a4-8c877de535f8)




---

3) # Blinkit Sales Performance Dashboard

---

### 📌 Objective:
- To provide a comprehensive view of Blinkit's sales performance across different outlet types, outlet sizes, and item categories.
- To help stakeholders monitor key sales trends, product category contributions, and outlet growth over time.
- To deliver actionable insights that support business expansion, operational improvements, and product optimization.

---

### 📈 KPIs Included:
- **Total Sales**: $1.20M
- **Average Sales per Item**: $141
- **Average Customer Rating**: 4
- **Total Number of Items Sold**: 9K

---

### 🚀 Key Features:
- **Dynamic Filter Panel**: Allows filtering based on Outlet Location Type, Outlet Size, and Item Type.
- **Sales Distribution**: View sales split by fat content (Low Fat vs. Regular) and across item categories (Fruits, Snacks, Household, etc.).
- **Outlet Establishment Trend**: Line chart visualizing outlet openings and performance from 2012 to 2022.
- **Outlet Size Analysis**: Sales breakdown by small, medium, and high-sized outlets using donut charts.
- **Outlet Location Insights**: Comparison of sales in Tier 1, Tier 2, and Tier 3 cities.
- **Outlet Type Metrics**: Tabular view showing total sales, number of items, average sales, ratings, and visibility for each outlet type.
- **Interactive and Clean Layout**: Ensures easy navigation and dynamic analysis for users.

---

### 🧠 Key Factors:
- Strong **Data Modeling** to manage complex relationships between outlets, sales, and product categories.
- Extensive use of **DAX** for calculated measures and KPIs.
- **Power Query** for data transformation and ETL processes.
- **Advanced Visual Design**: Focused on clarity, performance, and business relevance.

---

### ⚙️ Tools & Technologies Used:
- Power BI
- DAX (Data Analysis Expressions)
- Power Query (M Language)
- Data Modeling and ETL
- Visualization and UX Design

---

DaASHBOARD IMAGE: 
![6082508650414457962 (1)](https://github.com/user-attachments/assets/6d291d24-0809-4549-b80e-1a7323eaccf2)
