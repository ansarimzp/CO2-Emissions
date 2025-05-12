# 🌍 Global CO₂ Emissions Tracker by Sector

### 📊 Summary

This project delivers a comprehensive, interactive Power BI dashboard for monitoring carbon dioxide emissions across sectors, countries, and time. It integrates data science (Python), data modeling (SQL), and advanced visuals (Power BI) to support climate strategy, policy action, and sustainability reporting.

---

### 🧩 Problem Statement

> Climate reports often show totals, not trends.
> Decision-makers lack tools that answer:
> - Where are CO₂ emissions growing the fastest?
> - Which sectors are deviating from global norms?
> - Are policy changes impacting sustainability scores?

---

### 🎯 Project Objectives

- Detect and explain sector-level emission trends  
- Forecast next-year emissions using real-time data  
- Benchmark countries against global emission standards  
- Identify emission spikes and performance anomalies  
- Empower businesses and governments with actionable visual insights

---

### 🚀 What I Did (Key Contributions)

- Cleaned and structured 5+ years of CO₂ emission data using Python (Pandas).
- Used SQL to calculate year-over-year changes, emission spikes, and growth rates (CAGR).
- Built a **Power BI dashboard** with custom KPIs:  
  - **Z-Score Deviation**  
  - **Emission Spike Detection**  
  - **Environmental Score Forecast**  
  - **Country-Sector Rank & Contribution**

- Visuals include:
  - **Rolling Average Charts**
  - **Pie/Treemap by Sector Share**
  - **Forecast Line Graphs**
  - **DAX-based Waterfall & KPI Cards**
  - **Map visualization for country drilldowns**

---

### 📸 Dashboard Highlights (Screenshots)

#### 🟢 KPI Section
- Total Emissions: **319.49K**
- Spike Detection: **Triggered**
- Latest Year Value: **198.97**
- YoY % Change: **+0.03%**
 The dashboard highlights several advanced metrics: Percent change in emissions compared to the previous year, showing recent growth or decline.
CAGR (Compound Annual Growth Rate): Average annual growth rate over a multi-year period, summarizing long-term trends.
Z-Score: Statistical score of each sector-year value relative to its historical mean (in standard deviations), used to identify significant deviations or anomalies.
Forecast Score: Custom metric evaluating forecast accuracy (for example, R² or inverse MAPE), indicating how reliable the emissions projections are.
Emission Spike Detection: Identifies sudden emission jumps by comparing current values to a rolling baseline plus a threshold (e.g. 1.5 standard deviations).
### Key Insights & Findings
### The integrated SQL/Python analysis surfaces several interesting insights:
Brazil – Emission Spike: Our analysis flagged a pronounced one-time spike in Brazil’s CO₂ emissions, consistent with known surges in deforestation and agricultural activity.
Residential Sector: The forecast model predicts a gradual decline in the Residential sector’s emissions, suggesting ongoing efficiency improvements and a shift to cleaner household energy.
Ground Transport: This sector showed unusually high Z-scores in recent years, indicating emissions well above historical norms. The deviations likely reflect strong post-lockdown rebounds in vehicle use.
Sector Shares: Power generation and Industry dominate global emissions. In our data they account for the majority of CO₂ output (often over 60% combined), highlighting these sectors as primary targets for decarbonization.
Anomaly Years: The algorithm identified specific years with irregular emissions. For example, 2020 showed a dramatic drop in Transport and Industry emissions (pandemic effect), while other flagged years correspond to economic or policy shifts.

#### 📈 Forecast Panel
- Residential emissions forecasted to **decline**
- Power & Industry expected to **remain high**
- Aviation sectors show **low emissions but poor scores**

#### 📊 Sector Analysis
- Power, Ground Transport, and Industry show **highest CAGR**
- Residential has **high Z-score volatility** with moderate volume
- **Waterfall chart** explains YoY% Change vs CAGR by country & sector

#### 🗺️ Geomap View
- Highest emissions from **China**, **ROW**, **World Avg**, and **US**
- Bubble overlays show regional impact intensity

#### 🥧 Pie/Treemap View
- Clear visualization of **sector % share** per country
- Top categories: **Power**, **Domestic Aviation**, **Industry**

---

### 🧠 Advanced Business Insights

- 🔥 **Spike Detection Engine** flags countries with 30%+ emission jumps (e.g., Brazil pre-2022)
- 📉 **Environmental Scorecards** show sector-wise sustainability declines in Aviation & Residential
- 📊 **CAGR & Z-Score** used to track unsustainable growth (Power & Industry stand out)
- 🌍 **Country-Sector Drilldown** exposes regional drivers of pollution
- 🧮 **Forecast Models** help predict upcoming emission shifts for 2024

---

### 🛠 Tools & Technologies

| Tool       | Purpose                                        |
|------------|------------------------------------------------|
| **Python** | Data cleaning, formatting, and anomaly tagging |
| **SQL**    | Trend detection (CAGR, spike, rank, forecast)  |
| **Power BI** | Data modeling, KPI design, storytelling dashboard |
| **DAX**    | Calculations: YoY%, Z-Score, Forecast, Spike Flag |
| **Excel**  | Initial value checks and formatting            |

---

### 🗃 Files Included

| File                  | Description                                    |
|-----------------------|------------------------------------------------|
| `dataset.csv`         | Raw CO₂ emissions data (country, sector, year) |
| `emission_analysis.py`| Python file for EDA and preparation            |
| `SQL_queries.sql`     | Emission trend insights and transformations    |
| `Dashboard.pbix`      | Final Power BI dashboard file                  |
| `policy_brief.pdf`    | Executive summary for business presentation    |

---

### 💼 Use Cases

- 📊 **Climate Impact Analysis** for government policy teams  
- 🌱 **ESG Tracking** for corporate sustainability officers  
- 📉 **Emission Spike Alerts** for risk mitigation analysts  
- 🧠 **Data storytelling** in research and academic reports  
- 💬 Used in portfolio/project demonstrations for Data Analyst roles

---

### 🏁 Outcome

A fully interactive and data-rich dashboard that lets users:
- Detect country-sector-level anomalies in emissions
- Visualize environmental performance shifts over time
- Forecast future risks to align with global sustainability goals

> This dashboard transforms raw climate data into **real-time decision intelligence**.

---

### 📍 Live Preview

> 📷 Screenshots  
> 🟢 KPI Cards  
> 📈 Forecast Panels  
> 📊 Waterfall & Treemap  
> 🗺️ Country Map View

---
### Business and Policy Use Cases
The dashboard supports a range of real-world applications:
Government & Policy: Regulators can monitor sector-specific emissions to evaluate progress on climate targets and adjust regulations or incentives as needed.
Corporate Sustainability: Companies can benchmark their sector’s emissions against global trends, identify anomalies, and refine carbon-reduction strategies.
Investment & NGO Analysis: Investors and NGOs can spot high-growth emissions industries or countries, guiding investment decisions or advocacy focus.
Urban and Energy Planning: City planners and utilities can explore transport vs. residential emission patterns to prioritize infrastructure (e.g. public transit, building efficiency) for maximum impact.
Research & Reporting: Academics and international organizations can leverage the dashboard’s charts and KPIs for climate research, policy reports, and international comparisons.

### 👤 Author

**Name**: ALTAMASH ALI ANSARI   
**Role**: Data Analyst Intern  
**LinkedIn**: www.linkedin.com/in/altamash-ali-ansari-21482a260

---

🟢 *Feel free to fork, explore, or reach out to collaborate on climate analytics, Power BI, and sustainability data projects!*

