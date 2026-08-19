# ✈️ Airline Performance & Cancellation Analysis | Power BI

# 📸 Dashboard Preview

## ✈️ AIRLINE OVERVIEW
<img width="1378" height="781" alt="Airline_Overview" src="https://github.com/user-attachments/assets/94954347-bed7-4688-a257-93867b350731" />


## 📊 AIRLINE PERFORMANCE
<img width="1378" height="777" alt="Airline_Performance" src="https://github.com/user-attachments/assets/60384ae8-af6c-4564-8669-97fd74cf5031" />


## 🛫 ROUTE & AIRPORT Map
<img width="1383" height="776" alt="Airline_Route   Map" src="https://github.com/user-attachments/assets/9cf22727-762d-4235-8079-64cb7b488057" />


## 🔍 DRILL THROUGH
<img width="1377" height="776" alt="Airline_Drill-Through" src="https://github.com/user-attachments/assets/fd790639-fcc2-45c2-9702-8dfe8da05e20" />

## 📈 TREND & FORECAST
<img width="1379" height="782" alt="Airline_Trends   Forecast" src="https://github.com/user-attachments/assets/c65aabc9-80b6-4b4c-82de-ba1bf8655660" />

## 💡 TOOLTIP
<img width="1028" height="769" alt="Airline_Tooltip" src="https://github.com/user-attachments/assets/24d121c9-7423-435d-bf4d-2d8516d41f8a" />


---

## 📊 Project Overview

This project is an interactive **Power BI dashboard** built to analyze airline flight operations, cancellations, delays, on-time performance, routes, airports, and flight-volume trends from **2019–2023**.

The dashboard transforms airline data into meaningful business insights using **Power BI, DAX, Power Query, interactive filters, drill-through analysis, maps, and forecasting**.

---

## 📁 Dataset

Dataset: Flight Delay and Cancellation Dataset (2019-2023)
Source: Kaggle
Author: Patrick Zelazko 

**Dataset Link:**
https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023

## 🎯 Objectives

- Analyze total flight volume and airline performance
- Track flight cancellations and cancellation rates
- Identify major cancellation causes
- Analyze departure and arrival delays
- Measure yearly and monthly on-time performance
- Compare airlines based on flight volume
- Identify top destination airports
- Analyze airport and route performance
- Identify monthly and yearly flight trends
- Forecast future flight volume

---

## 📌 Key KPIs

| KPI | Result |
|---|---:|
| ✈️ Total Flights | **3M** |
| ❌ Total Cancelled | **79K** |
| 📉 Cancellation Rate | **2.64%** |
| ⏱️ On-Time Rate | **82.32%** |
| 🛫 Avg Departure Delay | **10.1 min** |
| 🛬 Avg Arrival Delay | **4.3 min** |

---

# 📑 Dashboard Pages

## 1️⃣ Airline Operations Overview Dashboard

Provides an executive summary of overall airline performance.

### Includes:
- Total Flights
- Total Cancelled Flights
- Cancellation %
- On-Time Rate
- Flight Cancellation by Cause
- Airline Comparison
- Flight Outcome Distribution
- Overall On-Time Rate vs 80% Target

---

## 2️⃣ Airline Performance Analysis Dashboard

Focuses on airline delays and cancellation performance.

### Includes:
- Top 10 Airlines by Average Departure Delay
- Top 10 Airlines by Cancellation Count
- Airline Cancellation Rate Heatmap
- Average Departure Delay
- Average Arrival Delay
- On-Time Performance

---

## 3️⃣ Airline Trends & Forecast Dashboard

Analyzes historical flight trends and future flight volume.

### Includes:
- Monthly Average Departure Delay by Year
- Monthly Flight Volume by Year
- Flight Volume Trend
- 6-Month Flight Volume Forecast

---

## 4️⃣ Airline Route & Airport Map Dashboard

Provides geographic and airport-level analysis.

### Includes:
- Total Flights by Airline
- US Departure Airport Flight Volume
- Average Airport Delay
- US State Cancellation Rate
- Geographic Flight Analysis
- Airport Performance

---

## 5️⃣ Drill-Through Detail Analysis

Allows users to select an airline and explore detailed performance.

### Includes:
- Airline-specific Flight Volume
- Cancellation Count
- Cancellation %
- Monthly Cancellation Trends
- Cancellation Causes
- On-Time Rate by Year
- Detailed Flight Records

---

## 6️⃣ Destination & Tooltip Analysis

Provides additional contextual analysis through interactive visuals and tooltips.

### 🛬 Top 5 Destination Airports

| Rank | Airport | Flights |
|---:|---|---:|
| 1 | **ATL** | 154K |
| 2 | **DFW** | 130K |
| 3 | **ORD** | 123K |
| 4 | **DEN** | 120K |
| 5 | **CLT** | 95K |

---

# 🔍 Key Insights

## ✈️ Overall Operations

The dataset contains approximately **3 million flights** with around **79K cancelled flights**, resulting in an overall cancellation rate of **2.64%**.

## ⏱️ On-Time Performance

The overall on-time rate is **82.32%**, exceeding the dashboard's **80% target**.

## ❌ Cancellation Causes

The major cancellation categories analyzed include:

- 🌦️ Weather
- 🔐 Security
- 🏛️ National Air System
- ✈️ Airline/Carrier-related cancellations

**Weather is the largest cancellation category in the analysis.**

## 🏆 Airline Flight Volume

**Southwest Airlines (WN)** has the highest flight volume in the dashboard, with approximately **576K flights**.

## 🛫 Top Destination Airports

| Rank | Airport | Flights |
|---:|---|---:|
| 🥇 1 | ATL | 154K |
| 🥈 2 | DFW | 130K |
| 🥉 3 | ORD | 123K |
| 4 | DEN | 120K |
| 5 | CLT | 95K |

---

# 🛠️ Tools & Technologies

- Power BI
- DAX
- Power Query
- Microsoft Bing/Azure Maps
- Data Modeling
- Time Intelligence
- Forecasting
- Data Visualization

---

# 📐 Power BI Skills Demonstrated

- DAX Measures
- Calculated Columns
- CALCULATE
- DIVIDE
- COUNTROWS
- AVERAGE
- Filter Context
- Date Table
- Relationships
- KPI Cards
- Slicers
- Drill-Through
- Tooltips
- Conditional Formatting
- Heatmaps
- Geographic Maps
- Forecasting
- Interactive Dashboards

---

# 🎛️ Interactive Filters

Users can dynamically filter the dashboard using:

- ✈️ Airline Code
- ⏱️ Delay Status
- 📅 Flight Year

All connected visuals update dynamically based on the selected filters.

---

# 📂 Repository Structure

```text
Power-BI-FlightDelay-Analysis/
│
├── README.md
├── PR_5.pbix
└── Output/
    ├── Airline_Overview.png
    ├── Airline_Performance.png
    ├── Airline_Trends & Forecast.png
    ├── Airline_Route & Map.png
    ├── Airline_Drill-Through.png
    └── Airline_Tooltip.png
```

# 💡 Business Value

This dashboard can help airline management and operations teams:

Monitor operational performance
Identify cancellation patterns
Track delays
Compare airline performance
Analyze airport activity
Monitor on-time performance
Identify high-volume airports and routes
Understand seasonal flight patterns
Forecast future flight demand
Support data-driven decision-making

# 🚀 Conclusion

The Airline Performance & Cancellation Analysis Dashboard provides a complete view of airline operations from 2019–2023.

By combining Power BI, DAX, Power Query, interactive visualization, geographic analysis, drill-through, and forecasting, this project demonstrates how raw airline data can be transformed into a professional and actionable Business Intelligence solution.


## ⭐ If you find this project useful

Feel free to explore the dashboard and dataset.

**Made with Power BI 📊**

## 👩‍💻 Author

**HAPPY PATEL**

Aspiring Data Analyst | Power BI | SQL | Python | Excel
