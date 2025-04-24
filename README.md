# 📊 Sales Performance & Profit Analysis Dashboard

![Insight Dashboard](./Insight%20Dashboard.png)
![Performance Insights Dashboard](./Performance%20Insights%20Dashboard.png)
![Profit Analysis Dashboard](./Profit%20Analysis%20Dashboard.png)

---

## 🚀 Project Overview

This project is an end-to-end **Sales and Profit Analysis Dashboard**, built using **SQL**, **Power BI**, and **Python**, aimed at uncovering business insights from raw sales data. The dashboard helps stakeholders analyze:

- Revenue trends and sales performance across markets
- Top performing customers and products
- Revenue and profit contribution by region
- Monthly profit margin trends and anomalies

---

## 📌 Tools & Technologies Used

- **SQL (MySQL)**: For data cleaning, transformation, and analysis
- **Power BI**: For interactive dashboard design and data visualization
- **Python** *(Optional scope/extension)*: Can be used for EDA, forecasting, or anomaly detection (not used in dashboard, but can be extended)

---

## 📂 Project Files

| File Name                         | Description                                              |
|----------------------------------|----------------------------------------------------------|
| `Insight Dashboard.png`          | Revenue & Sales Quantity Analysis                        |
| `Performance Insights Dashboard.png` | Profit Margin, Revenue Contribution & Customer Analysis |
| `Profit Analysis Dashboard.png`  | Market-wise Profit Contribution & Trend Analysis         |
| `sales_dashboard.pbix`           | Power BI project file                                    |
| `db_dumb_version_2.sql`          | SQL script for database schema and data population       |

---

## 🔧 Process & Workflow

### 1. Data Preparation in SQL
- Loaded raw sales datasets into a MySQL database.
- Performed data cleaning: handled NULLs, filtered irrelevant records, created joins across sales, customer, and product tables.
- Created views and summary tables for performance metrics like revenue, sales quantity, and profit margin.
- Extracted insights using SQL queries.

### 2. Power BI Dashboard Design
- Connected Power BI directly to the SQL database.
- Modeled relationships between tables and created calculated fields.
- Built interactive visuals:
  - **Bar charts** for market-level breakdowns
  - **Line graphs** for trend analysis
  - **Tables and KPIs** for customer-level metrics and key figures
- Incorporated slicers to allow dynamic filtering by time and geography.

### 3. Version Control & Documentation
- Uploaded all files and dashboard screenshots to GitHub for easy access.
- Documented the project with clear descriptions and visual previews.

---

## 📈 Key Insights Derived

- Delhi NCR generated the highest revenue but had low profit contribution.
- Some markets like Lucknow and Kanpur had negative profit margins.
- A small group of customers contributed disproportionately to total revenue.
- Profit margins declined significantly in Q2 2020, flagging a potential operational issue.

---

## ✅ How to Use This Project

1. Clone the repository
2. Use the `.sql` file to recreate the database
3. Open the `sales_dashboard.pbix` in Power BI Desktop
4. Connect it to your local SQL server (adjust credentials if needed)
5. Explore and interact with the dashboards

---

## 🧠 Skills Demonstrated

- End-to-end project execution using real business logic
- Strong SQL-based data transformation and aggregation
- Advanced Power BI dashboarding and DAX calculations
- Business acumen through actionable data storytelling
