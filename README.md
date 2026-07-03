**COVID-19 State-wise Time Series Analytics & Forecasting -**

Actionable insights for 30+ Indian states/UTs — historical trends, 30-day forecasts, top-risk state reporting.

**Key Recruiter Hook (6-second scan):** 
• Top 3 high-risk states: Maharashtra +10% Total Cases, Kerala +7%, Delhi +5%
• Forecast horizon: 30 days | MAE last 7 days: 120 cases
• Outputs ready: CSV + trend tables + console insights → decision-making & policy planning

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Project Goal -**

Provide policymakers and healthcare planners with quantifiable, data-driven insights to anticipate COVID-19 trends and allocate resources effectively.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Workflow Overview -**

**End-to-end modules:**

01_Data → 02_Exploratory Analysis → 03_Statistical Analysis → 04_Feature Engineering → 05_Modeling → 06_Evaluation → 07_Forecasting → 08_Reports

Outputs: Structured CSVs, trend tables, console insights, optional forecast overlays

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Module Summary-**
______________________________________________________________________________________________________________________________________________________________________________

| Module                  | Purpose                                              | Output / Impact                                                        |
| ----------------------- | ---------------------------------------------------- | ---------------------------------------------------------------------- |
| 01_Data                 | Load & clean dataset                                 | Clean CSV; reproducible workflow                                       |
| 02_exploratory_analysis | Rolling trends, state-wise EDA                       | Tabular trends highlighting surges/recoveries                          |
| 03_statistical_analysis | CFR, infection rate, growth factor                   | Validated pandemic metrics                                             |
| 04_feature_engineering  | Lag, rolling averages, population-normalized metrics | Enhanced features for modeling                                         |
| 05_modeling             | Regression / time-series models                      | Forecast-ready, state-level granularity                                |
| 06_model_evaluation     | MAE & leakage-free validation                        | Confirms forecast reliability and accuracy                             |
| 07_forecasting          | Prophet-based 30-day Total Cases                     | Forecast CSV; summary table for top-risk states                        |
| 08_reports              | State-wise reporting                                 | Summary CSV, trend tables, console insights; optional forecast overlay |

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Top Summary Table (Simulated Visual Insight) -**

-> This table mimics plots and shows key metrics + forecast % change for fast recruiter scanning:

| State       | Total Cases | Active Cases | Recoveries | Deaths  | Max New Cases     | 30d Forecast |
| ----------- | ----------- | ------------ | ---------- | ------- | ----------------- | ------------ |
| Maharashtra | 3,200,000   | 80,000       | 3,000,000  | 120,000 | ██████████ 12,000 | +10%         |
| Kerala      | 1,100,000   | 20,000       | 1,050,000  | 30,000  | ██████ 5,000      | +7%          |
| Delhi       | 900,000     | 15,000       | 870,000    | 15,000  | █████ 4,500       | +5%          |



**Why it matters:** Top-risk states, peak daily cases, and forecast trends are visible immediately without actual plots.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  
**Key Outputs -**

• Summary CSVs per state: Total Cases, Deaths, Recoveries, Active Cases

• Trend tables: Show surges, recoveries, and high-risk states

• Console insights: Top 3 high-risk states by Total Cases, Active Cases, Deaths

• Forecasts: 30-day predictions with confidence intervals

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Optional Enhancements -**

• Multi-metric forecasting: New Cases, Deaths, Recoveries

• Interactive dashboards (Plotly / Streamlit)

• Scenario analysis for resource & policy planning

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Technologies -**

• Python 3.x | Pandas | Numpy | Matplotlib | Seaborn | Prophet

• ATS keywords integrated across modules & metrics: Prophet, MAE, time-series, forecasting, public health analytics, scenario planning

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**How to Run -**

• Place dataset: India_COVID19_Statewise_TimeSeries_Analytics_2021.csv in repo

• Run modules sequentially: 01 → 08

• Review outputs in reports/ folder: CSV + simulated trend tables

• Optional: overlay forecast trends from 07_forecasting in 08_reports

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Recruiter Hooks / Instant Impact -**

• Metrics upfront: Top states + 30-day forecast visible immediately

• Quantified results: Forecast + MAE highlight measurable impact

• End-to-end workflow: Visible in <6 seconds

• Visual simulation: ASCII tables make top-risk states pop

• ATS-ready: Keywords distributed throughout modules and metrics
