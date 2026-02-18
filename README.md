# Walmart Sales Performance Analysis (2010–2012)

## 📌 Project Overview

This project analyzes Walmart’s sales performance from 2010 to 2012 using a dashboard-driven retail analytics approach. The objective is to understand sales trends, store performance, promotional impact, seasonality, and the influence of external economic factors to support data-driven retail decision-making.

The analysis simulates a real-world retail analytics challenge faced by large retail chains operating multiple stores across regions.

## 🎯 Business Objectives

- Evaluate overall revenue growth across years (2010–2012)
- Identify high-performing stores and store types
- Analyze seasonal and yearly sales fluctuations
- Assess the impact of promotional markdowns on sales
- Understand the influence of external economic factors such as fuel price

---

## 📊 Dataset Description

- **Source:** Walmart Weekly Sales Dataset (Kaggle)
- **Time Period:** 2010 – 2012
- **Granularity:** Weekly, store-level and department-level
- **Key Variables:**
  - Store, Dept, Date
  - Weekly_Sales
  - Store Type, Store Size
  - MarkDown1–5
  - Temperature, Fuel_Price
  - CPI, Unemployment
  - IsHoliday

---

## 🧹 Data Cleaning & Preparation

- Converted text-based dates into standard date format using `DATEVALUE()`
- Replaced missing markdown values with `0` (indicating no promotion)
- Imputed missing CPI and unemployment values using column averages
- Validated numeric formats and removed inconsistencies

---

## 📈 KPI & Metrics

- **Total Sales**
- **Average Weekly Sales**
- **Total Markdown**
- **Total Transactions**
- **Average Fuel Price** (supporting KPI)

These KPIs were used to track performance, consistency, promotional effectiveness, and economic sensitivity.

---

## 🔍 Exploratory & Advanced Analysis

- Identified a sales dip in 2011 followed by recovery in 2012
- Store Type A contributes the majority of revenue
- Revenue concentration observed among top-performing stores
- Promotions significantly increase sales
- Strong seasonal and holiday-driven demand patterns
- Limited short-term impact of economic indicators on sales

---

## 📊 Dashboard Design

- **Tool Used:** Google Sheets
- Includes:
  - Executive KPI overview
  - Store and store-type performance comparison
  - Promotion and seasonality analysis
  - Economic context indicators
- Interactive filters for year, store type, and holiday periods

---

## 💡 Key Insights

- Business shows resilience with strong post-2011 recovery
- Heavy dependence on Store Type A and top stores
- Promotions are effective but require optimization
- Clear seasonality can guide inventory and staffing planning

---

## 📌 Recommendations

- Reduce revenue concentration by improving mid-performing stores
- Optimize promotion strategy to avoid margin erosion
- Strengthen underperforming stores with localized planning
- Improve seasonal inventory and staffing preparation
- Monitor economic indicators for proactive planning

---

## ⚠️ Limitations

- Analysis based on historical data (2010–2012)
- Promotion profitability not evaluated
- Limited external variables considered
- No predictive modeling implemented

---

## 🔮 Future Scope

- Implement sales forecasting models
- Extend analysis to profitability and margin data
- Add real-time dashboard integration
- Include additional external factors (competition, online sales)

---

## 🛠 Tools & Technologies

- Google Sheets (Data Cleaning, Analysis, Dashboard)
- Excel Functions (DATEVALUE, aggregation formulas)
- KPI-driven dashboard analytics

---

## 👥 Contributors

- Bhavay Goyal
- Manpreet Singh
- Udata Varun
- Ritesh
- Kevish Sewliya
- Siddarth Dangi

---

## ✅ Conclusion

This project demonstrates how structured data analysis and dashboards can convert raw retail data into actionable business insights, supporting strategic decision-making, operational efficiency, and sustainable growth in large-scale retail environments.
