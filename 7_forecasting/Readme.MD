**COVID-19 Total Cases Forecasting per Indian State/UT -**

Predicts 30-day COVID-19 total cases per State/UT in India using Prophet—actionable insights for policymakers and healthcare planners.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**📌 Purpose -**

Provides short-term forecasts of COVID-19 total cases for all Indian States/UTs using **Prophet**, enabling proactive healthcare planning, resource allocation, and policy decision-making.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**📊 Dataset -**

- Source:  'India_COVID19_Statewise_TimeSeries_Analytics_2021.csv'

- Key columns: `Date`, `State_UT`, `Population`, `New_Cases`, `New_Deaths`, `New_Recoveries`, `Total_Cases`, `Total_Deaths`, `Total_Recoveries`, `Active_Cases`

- Data spans multiple States/UTs across India.

----------------------------------------------------------------------------------------------------------------------------------------------------------------

**🛠 Approach -**

1. Clean and preprocess dataset (handle missing values, convert `Date` to datetime).  

2. Forecast `Total_Cases` per State/UT using Prophet (time series modeling). 

3. Forecast horizon: 30 days into the future.  

4. Evaluate forecast accuracy using **MAE for last 7 days**. 

5. Visualize actual vs predicted cases with **confidence intervals**. 

6. Save forecast plots per state (`forecast_<State_UT>.png`) in an organized folder.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

**📈 Output -**

- State-wise forecast plots showing actual vs predicted total cases with confidence intervals.  

- MAE (last 7 days) for each state to show forecast reliability.  

- Clean, recruiter-friendly folder structure: `forecasts/`.

**💡 Key Insights / Impact -**

- Identifies potential COVID-19 surges across states.  

- Supports resource allocation and proactive policy-making. 

- Demonstrates end-to-end forecasting workflow on real-world pandemic data.  

- Provides actionable, interpretable visualizations for decision-makers.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

**🔧 Technologies -**

- Python 3.x, Pandas, Matplotlib, Prophet (Meta/Facebook)  

------------------------------------------------------------------------------------------------------------------------------------------------------------------

** 🚀 Optional / Bonus Topics -**

- Multi-metric forecasting: `Active_Cases`, `New_Cases`. 

- Interactive dashboards (Streamlit / Plotly) for real-time visualization.  

- Scenario analysis / what-if predictions for policy planning.

- Comparison with other models (ARIMA, LSTM) for advanced analysis.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

** ✨ Next Steps / Collaboration -**

- Extend forecasting to additional metrics like `Active_Cases` and `New_Cases`. 

- Compare Prophet vs LSTM models for improved accuracy.  

- Open to collaboration for multi-state COVID prediction pipelines.

