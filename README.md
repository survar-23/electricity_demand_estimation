**_Electricity Demand Forecasting_**

Overview

This repository provides insights into forecasting electricity demand for the next 1–2 years using advanced time series models. These forecasts aim to support strategic planning for electricity production and vendor management for a prominent electricity distribution company.

Business Requirement: The electricity distribution company seeks accurate demand forecasts to:

- Optimize electricity production and procurement.
- Align production with market needs.
- Enhance vendor relationship management.
- Reliable forecasting is critical for ensuring efficient energy management and meeting future demand.

Data Availability: The dataset contains monthly electricity consumption data from January 1973 to December 2019, with the following key variables:
- Date: Represented by Month and Year.
- Electricity Consumption: Measured in Trillion Watts.

Objective: The objective is to develop a reliable demand forecasting model for the next 1–2 years by leveraging historical consumption data.

Models Used

The following time series forecasting models are applied to generate predictions:

1. Exponential Smoothing (ETS)

Description: A statistical method that smooths data points by assigning exponentially decreasing weights over time. Suitable for data with trends and seasonality.
Key Features: Handles level, trend, and seasonal components effectively.
Model Visualization:

![image](https://github.com/user-attachments/assets/2c9801d3-3a90-433f-9b71-8c6f35d4219c)


2. ARIMA (AutoRegressive Integrated Moving Average)

Description: ARIMA is a robust model for analyzing and forecasting time series data. It accounts for patterns of autocorrelation, trend, and noise.
Key Features: Effective for univariate data without seasonal effects.
Model Visualization:

![image](https://github.com/user-attachments/assets/89916cff-a4fe-4244-adc0-a13f8a6a3aac)


3. SARIMA (Seasonal AutoRegressive Integrated Moving Average)

Description: SARIMA extends ARIMA by incorporating seasonal patterns in the data, making it ideal for datasets with periodic behavior.
Key Features: Handles both trend and seasonality.
Model Visualization:

![image](https://github.com/user-attachments/assets/ea24e199-4f6b-47f3-95f7-1864be6a2302)

