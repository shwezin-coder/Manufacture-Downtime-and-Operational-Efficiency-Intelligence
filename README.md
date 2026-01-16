# Manufacture-Downtime-and-Operational-Efficiency-Intelligence
🚀 Project Overview
This project involved architecting a professional business intelligence solution to monitor, simulate, and mitigate manufacturing downtime for a high-volume production facility. I designed a multi-layered dashboard suite that translates raw operational logs into strategic financial insights for C-Level executives and granular root-cause analysis for operational teams. By implementing advanced What IF simulations and Market Basket Analysis on downtime causes, I identified a potential annual saving of over $770K.

<img width="1592" height="1098" alt="image" src="https://github.com/user-attachments/assets/7f57494b-c971-4b04-858f-3a95f7868a5f" />


🛠️ Tech Stack
Analytics & Visualization: Power BI (Advanced DAX, Power Query).

Data Modeling: Star Schema Architecture.

Analysis Techniques: Predictive Forecasting, What-IF Simulation, Market Basket Analysis.

📊 Data Architecture (4-Table Star Schema)
I engineered a high-performance Star Schema designed for analytical scalability to ensure data integrity across all reporting layers:

Fact Tables:

fact_line_productivity: The core transactional table tracking batch-level performance, duration, and operator assignments.

fact_line_downtime: A granular fact table capturing individual downtime events, durations, and calculated financial costs.

Dimension Tables:

dim_products: Stores product-specific benchmarks, including Flavor, Min batch time, and Production Cost per Unit.

dim_downtime_category: Classifies downtime by Description and Factor to enable error-type segmentation.

💡 Technical Innovation and DAX Intelligence
Executive Strategic Insights (C-Level Dashboard)
Financial Impact: Tracked a total downtime cost of $5.55M, utilizing Time-Intelligence DAX to monitor Current Year (CY) vs. Previous Year (PY) performance.

Productivity Benchmarking: Designed gauge visualizations showing a Net Productivity Rate of 71% against a target benchmark of 85%, identifying a loss of 2,932 working hours.

Human Error Segmentation: Discovered that Human Error accounts for 89% of all downtime costs, specifically highlighting product spills and calibration errors as major culprits.

<img width="1549" height="905" alt="image" src="https://github.com/user-attachments/assets/bec6960b-8271-4477-8433-a0ea98e03fb2" />


Predictive "What-IF" and Action Forecasting
Forecasting Models: Engineered an Action Forecasting tool using DATEADD and DIVIDE to simulate future downtime costs based on historical growth trends.

ROI Simulation: Built an interactive What-IF Analysis tool where management can adjust a Downtime Reduce Percentage parameter.

Forecasted Savings: A 20% reduction in major errors was shown to result in $776K in annual savings.

<img width="1302" height="1240" alt="image" src="https://github.com/user-attachments/assets/8a5e1f8c-98ea-4d0d-927b-7586eba419c6" />


Root-Cause and Shift Analysis
Market Basket Analysis: Created a calculated table (pair_reasons) to identify "co-occurring errors"—causes that frequently happen together during the same batch.

Shift Performance: Identified that Afternoon and Midnight shifts record the highest downtime, signaling a need for stricter supervision or process discipline.

Advanced Drill-Through: Engineered a seamless transition from high-level "Excess Group" metrics down to individual Batch ID transaction details.
<img width="1005" height="1217" alt="image" src="https://github.com/user-attachments/assets/fdacb47d-21b1-4dd2-88b4-218f0fce164a" />


📈 Impact and Actionable Outcomes
Targeted Training: Shifted company investment from machine upgrades to a Targeted Training Program focusing on the four major causes: spills, coding, calibration, and label switches.

Operational Discipline: Recommended Standardized Operating Procedures (SOPs) specifically for high-risk shifts and the CO-2L product line.

Process Improvement: Demonstrated the ROI of System Validation Automation to minimize manual input mistakes during batch coding.

<img width="1328" height="1324" alt="image" src="https://github.com/user-attachments/assets/27d1567e-12d2-4631-87a7-59b6d7ba149e" />
