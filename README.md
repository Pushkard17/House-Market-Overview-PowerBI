# House Market Overview Dashboard (Power BI)

## 📌 Project Overview
This **end-to-end Power BI project** analyzes the housing market, including sales trends, regional pricing, and property insights.  
Data is sourced from:
- **Google BigQuery** – Market and demographic datasets
- **MS SQL Server** – Historical house sales and transactions

The dashboard provides interactive reports to understand housing trends, pricing patterns, and investment opportunities.

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** – Visualization & DAX calculations
- **MS SQL Server** – Source database for historical sales
- **Google BigQuery** – Cloud database for market/demographic data
- **SQL** – Queries for data extraction & transformations
- **DAX** – Measures & KPIs in Power BI

---

## 📊 Dashboard Features
- **Sales Trends** – Month-wise & region-wise house sales
- **Price Analysis** – Average and median pricing per region
- **Market Insights** – Property type distribution and trends
- **Regional Comparison** – Compare neighborhoods or states
- **Interactive Filters** – Price range, location, property type

---

## 📂 Repository Structure

---

## ⚡ Data Flow (Architecture)
1. **MS SQL Server** – Houses historical sales data.
2. **Google BigQuery** – Provides market, demographic, and supplementary datasets.
3. **Power BI** – Connects to both sources via DirectQuery/Import to build interactive dashboards.

---

## 📸 Dashboard Preview
![Overview](Screenshots/overview.png)  
![Sales Trends](Screenshots/sales_trends.png)  
![Region Analysis](Screenshots/region_analysis.png)  

---

## 🚀 How to Use
1. Clone or download the repo.
2. Open `Dashboard.pbix` in **Power BI Desktop**.
3. Update connections to your **BigQuery & MS SQL credentials**.
4. Refresh dataset to load live data.
5. Explore visualizations and reports.

---

## 🔑 Key Insights
- Identified fastest-growing neighborhoods in terms of sales volume.
- Average house prices increased by **X%** year-over-year in major regions.
- Certain property types show higher ROI for investors.
- Regional comparisons highlight underpriced areas for potential investment.

---

## 📧 Contact
Created by **[Pushkar Dhavane]**  
Reach out via GitHub or LinkedIn for questions.
