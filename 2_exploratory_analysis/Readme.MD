**Exploratory Data Analysis – COVID-19 Time Series**

------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Objective -**

To analyze temporal case progression, volatility behavior, and growth dynamics in COVID-19 data to prepare a statistically sound foundation for forecasting and time-series modeling.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**Business Context -**

Unstructured case data leads to biased forecasting and unreliable trend interpretation.
This analysis establishes trend clarity, noise reduction, and temporal dependency understanding before model development.

---------------------------------------------------------------------------------------------------------------------------------------------------------------

**Dataset Handling -**

df =pd.read_csv("/content/sample_data/India_COVID19_Statewise_TimeSeries_Analytics_2021.csv")

-> Structured loading ensures reproducibility and pipeline alignment.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

**Analytical Focus Areas -**

• Time-series trend visualization

• Daily growth rate computation

• 7-day rolling mean smoothing

• Volatility measurement

• State-level comparative behavior

• Surge detection and wave pattern identification

------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Key Insights -**

• Case growth follows identifiable surge cycles rather than random spikes.

• Short-term volatility reduces significantly after rolling window smoothing.

• Mortality trends demonstrate lag dependency on confirmed cases.

• High population states do not proportionally translate to higher fatality ratios.

• Growth acceleration periods align with identifiable wave phases.

------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Technical Stack -**

• Python

• Pandas

• NumPy

• Matplotlib

• Seaborn

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**Outcome -**

• Built reproducible EDA workflow aligned with forecasting requirements

• Identified lag relationships critical for ARIMA modeling

• Reduced noise using rolling aggregation techniques

• Prepared dataset for statistical stationarity testing

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**Skills Demonstrated (ATS Aligned) -**

Time Series Analysis | Data Cleaning | Feature Engineering | Statistical Thinking | Trend Analysis | Data Visualization | Forecasting Preparation | Python | Pandas
