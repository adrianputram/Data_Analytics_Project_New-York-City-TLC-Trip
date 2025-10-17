# 🚖 NYC TLC Trip Record Analysis

**Author:** [Your Name]  
**Capstone Project – Module 2 (Data Analytics Program)**  

---

## Project Overview

This project analyzes taxi and limousine trip records from **New York City’s Taxi and Limousine Commission (TLC)** to uncover insights about **customer demand, revenue optimization, and operational efficiency**.  

By applying data analysis and visualization techniques, this project aims to help taxi companies:
- Understand **peak demand periods** and high-demand areas,  
- Identify **factors affecting fare amounts and tips**,  
- Evaluate **vendor performance** and improve operational efficiency,  
- Enhance **customer satisfaction** through data-driven decisions.

The final outcome includes an **interactive Tableau dashboard** and a **comprehensive exploratory analysis** performed in Python.

---

## Data Sources

- **Dataset:** New York City Taxi & Limousine Commission (TLC) Trip Record Data  
  (Public dataset provided by NYC Open Data)
- **Files Used:**
  - `NYC_TLC_Trip_Record.csv` – Raw trip data  
  - `NYC_TLC_Sample_For_Tableau.csv` – Cleaned and sampled data for visualization  
  - `NYC TLC Trip Record Data Dictionary.pdf` – Variable definitions  
  - `Capstone Project Module 2 Guideline.pdf` – Project instructions  

---

## Technologies Used

| Category | Tools / Libraries |
|-----------|-------------------|
| **Programming & Analysis** | Python, Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Tableau Public |
| **Environment** | Jupyter Notebook |
| **Version Control** | Git & GitHub |

---

## Summary of Findings

### Demand Analysis
- Peak demand occurs between **6:00 PM – 9:00 PM**, especially on **Fridays and Saturdays**.  
- Weekday demand follows typical commuting patterns, with moderate activity in the mornings.

### Revenue Insights
- **Trip distance** is strongly correlated with **fare amount**.  
- **Average fare** and **tips** increase significantly during evening hours.  
- **Credit card** payments tend to yield higher tips than cash.

### Operational Efficiency
- **Vendor 2** demonstrates shorter average trip durations and higher operational efficiency compared to **Vendor 1**.  
- Trips with `store_and_fwd_flag = Y` are rare and likely caused by temporary connectivity issues.

### Geographic Trends
- High-demand areas include **Manhattan** and **airport zones (JFK, LaGuardia)**.  
- Airport-related trips contribute to higher average fares and longer durations.

### Key Recommendations
- Allocate more taxis in **high-demand zones** during **evening peak hours**.  
- Encourage **digital payments** to increase tip revenue.  
- Implement **dynamic pricing** during peak hours to maximize income.  
- Benchmark Vendor 1 operations against Vendor 2 for efficiency improvement.

---

## Tableau Dashboard

🔗 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/NYCTLCTripRecordAnalysis/NYCTaxiDashboard)

The Tableau dashboard visualizes:
- Hourly and weekly trip demand  
- Average fare per hour  
- Tip amount by payment type  
- Trip duration by vendor  

This dashboard allows management to **monitor performance, identify trends, and make data-driven decisions** in real time.

---

## Conclusion

This analysis demonstrates how data from NYC’s taxi industry can be leveraged to optimize **operations, pricing strategies, and customer satisfaction**.  
By combining Python-based exploratory analysis with Tableau visualization, this project provides an actionable business intelligence solution for transportation companies.

