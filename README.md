# Healthcare Productivity Trends Dashboard (2009–2013)

## 📌 Project Overview

The *Healthcare Productivity Trends Dashboard* is an interactive Excel-based analytics tool that provides deep insights into workforce productivity across California’s healthcare facilities. The analysis focuses on *productive hours, **adjusted patient care, and **control types* of hospitals (e.g., City/County, Investor-owned, Non-Profit) over a 5-year period (2009–2013).

Developed using Microsoft Excel, the dashboard uses *pivot tables, slicers, dynamic charts*, and structured data visualizations to allow users to easily filter, compare, and evaluate trends at both macro (state-wide) and micro (county-level) scales.

---

## 🧭 Business Context & Objective

Healthcare systems are constantly under pressure to deliver more care with limited resources. Workforce productivity—defined by the number of hours worked and the efficiency of time spent per patient—is a critical success factor for any health system.

This dashboard was developed to:

- *Track trends in workforce usage* over time
- *Identify disparities* across counties and facility types
- *Provide decision-makers* with actionable metrics to guide resource allocation and workforce planning
- Highlight potential inefficiencies or underperforming entities within the system

---

## 📂 Dashboard Composition & Features

### 1. *Slicers (Filters)*
- *Year (2009–2013)* — Enables time-series analysis
- *Control Type* — City/County, District, Investor, Non-Profit, State
- *County* — Filters results to specific geographic areas

### 2. *Charts & Visuals*
- 📈 *Line Chart*: Average Productive Hours per Year
- 📊 *Bar Chart*: Normalized Hours by Hour Type
- 🥧 *Pie Chart*: Percentage of Total Hours by Control Type
- 📊 *Bar Chart*: Total Productive Hours by Control Type (Yearly)
- 📈 *Line Chart*: Hour per Adjusted Patient Day Over Time
- 📉 *Bar Chart*: Productive Hours by County

### 3. *Tabular Insights*
- Count of facilities by control
- Summary of average hours per control/county/year

---

## 📈 Analytical Findings & Insights

### 🔹 Dominance of Public Sector Control
- City/County facilities account for *71.71%* of total productive hours, vastly outnumbering private or investor-controlled entities.
- This signals the *strong presence of public infrastructure*, but also questions the capacity of private sector contributions.

### 🔹 Positive Trend in Workforce Output
- Average productive hours increased steadily:
  - 2009: ~210,000 hrs
  - 2013: ~214,466 hrs
- This may reflect *growth in staffing*, better workforce planning, or increased patient volume.

### 🔹 Improving Per Patient Focus
- Hours per adjusted patient day rose from *3.05 (2010)* to *3.18 (2013)*.
- Indicates a trend toward *more direct care per patient*, which could imply improved service delivery or higher patient demands.

### 🔹 Geographic Inequality in Workforce Utilization
- *Alameda County* ranks consistently high in total productive hours, while *Amador and Alpine counties* remain underrepresented.
- This discrepancy may result from population size differences, resource availability, or hospital capacity.

### 🔹 Imbalanced Hour Type Utilization
- Majority of hours fall into a few broad categories like *Direct Care* and *Support Services*, while others are rarely utilized.
- Suggests a potential misalignment of staff assignments or underuse of specialized roles.

---

## ⚠ Identified Lapses & Data Gaps

1. *Underreporting from Private Sector*
   - Investor and Non-Profit facilities account for less than *10%* combined of total hours, raising concerns about data completeness or underperformance.

2. *Missing Contextual KPIs*
   - No data on *patient outcomes, **readmission rates, or **financial efficiency*. This limits the ability to correlate productivity with care quality.

3. *County Gaps*
   - Several counties have minimal or no recorded data for certain years, suggesting *incomplete reporting* or inconsistencies in data gathering.

4. *Static Data Set*
   - The Excel model relies on manually updated data. For ongoing operational use, this poses a scalability issue.

---

## ✅ Recommendations

### 1. *Expand KPI Scope*
Incorporate:
- Patient satisfaction
- Operational costs
- Staff-to-patient ratios
- Clinical outcomes

This would allow the productivity analysis to be more holistic and actionable.

### 2. *Normalize Metrics for Fair Comparison*
- Introduce *population-adjusted* metrics (e.g., hours per 1,000 residents) to avoid penalizing small counties.
- Use facility size and patient volume as normalizing factors.

### 3. *Automate Data Integration*
- Use *Power Query* or integrate with SQL/CSV pipelines to auto-refresh dashboards with new data.

### 4. *Benchmarking Framework*
- Establish *benchmarks* for hours per patient, staff utilization, and facility efficiency across similar control types or counties.

### 5. *Engage Private Sector*
- Encourage consistent data submission from investor-owned and non-profit entities to complete the full healthcare landscape.

---

## 🛠 Tools & Technologies Used

- *Microsoft Excel*
  - Pivot Tables
  - Slicers
  - Data Cleaning
  - Dynamic Charting
- *Data Source*: Cleaned hospital-level productivity data (CSV/Excel)
- *Design Approach*: Interactive dashboard with filters and automated summaries

---

## 🧑‍💼 Author Information

*Okoronkwo Ifeanyi Eric*  
Data Analyst | Freelance   
🔗 LinkedIn: [www.linkedin.com/in/ifeanyieric](https://www.linkedin.com/in/ifeanyieric)  
📅 Date: June 2025  
📍 Nigeria

> I'm passionate about driving healthcare transformation through data. This project reflects my commitment to using analytical tools to uncover operational insights and improve system-wide performance.

---

## 📄 License

MIT License

Copyright (c) 2025 Okoronkwo Ifeanyi Eric

Permission is hereby granted, free of charge, to any person obtaining a copy  
of this software and associated documentation files (the "Software"), to deal  
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all  
copies or substantial portions of the Software.

**THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE  
SOFTWARE.**

---

## 🙌 Acknowledgements

I would like to acknowledge the creators and maintainers of the healthcare datasets used in this project. Although I do not have a background in clinical or healthcare operations, this project was driven by curiosity and the need to apply data analysis skills in a real-world context.

Special thanks to:
- Public health institutions and open data platforms that make this type of analysis possible.
- Data professionals and visualization experts whose work continues to inspire and guide my learning journey.

This dashboard is a data-driven research artifact, and I welcome constructive feedback or collaboration to improve it.
