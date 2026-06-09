# Maven Market Topline Performance Dashboard

## 📊 Project Overview
An interactive Power BI dashboard designed to analyze and track key retail performance metrics for Maven Market across North America (1998). 

### 🖼️ Dashboard Preview
![Topline Performance](Screenshot%202026-06-09%20222445.png)

## 💡 Key Features & Insights
* **Executive KPIs:** Real-time tracking of Current Month Transactions, Profit, and Returns against monthly targets.
* **Geographic Drill-Down:** Advanced Treemap architecture allowing seamless drill-down from Country -> State -> City level.
* **Data-Driven Matrix:** Showcases top 30 product brands sorted by total transactions, complete with visual data bars and conditional formatting gradients.
* **Interactive Bookmarks:** Implemented custom storytelling bookmarks (e.g., "Portland 1000 Sales") tied to dynamic navigation buttons.

## 🛠️ Tech Stack & DAX Formulas Used
* **Tool:** Power BI Desktop
* **Data Modeling:** Star Schema (Fact and Dimension tables)
* **Key DAX Concepts:** Time Intelligence (`Last Month Profit`, `Last Month Transactions`), KPI target modeling, and conditional color scaling.
