# Walmart Sales Analysis

This repository contains an analysis of weekly sales data from Walmart stores. The dataset includes various features such as store number, date, weekly sales, holiday flag, temperature, fuel price, CPI (Consumer Price Index), and unemployment rate. The analysis aims to explore various aspects of the dataset and extract insights from it.

## Dependencies
The analysis was conducted using Python with the following libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `plotly.express`
- `statsmodels`

## Analysis Overview
1. **Data Cleaning and Preprocessing**: The dataset was loaded into a Pandas DataFrame. The data types were corrected, and date columns were converted to the proper format. Null values were checked and handled appropriately.

2. **Exploratory Data Analysis (EDA)**:
   - Descriptive statistics were computed to understand the central tendencies and distributions of the features.
   - Box plots were created to identify outliers and understand the distribution of numerical features.
   - Time series plots were generated to visualize the trends in weekly sales, temperature, fuel price, and other variables over time.
   - Heatmap was plotted to analyze the correlation between different features.

3. **Insights Obtained**:
   - Temperature: There's an observation that sales are lower during summer months compared to winter, indicating people tend to shop less in hot weather.
   - Holiday Flag: Sales show spikes during holiday periods, especially in December.
   - Fuel Price: There's an observation that fuel prices increase over time due to inflation but have no direct correlation with sales.
   - Unemployment Rate: Unemployment doesn't significantly affect sales but decreases over time.
   - Consumer Price Index (CPI): CPI doesn't have a direct correlation with sales over time.

4. **Top Performing Stores**: Store 20 was identified as the top-performing store, while Store 33 was identified as the worst performing store. The difference between the highest and lowest performing stores' weekly sales was approximately $264,237,570.

5. **Time Series Analysis**: A time series analysis was conducted using ARIMA modeling to identify trends, seasonality, and residuals. Rolling statistics and seasonal decomposition were also performed to understand the patterns in weekly sales data.Futher, The next 12 weeks of sales was predicted.

## Conclusion
This analysis provides valuable insights into Walmart's weekly sales data, identifying factors such as seasonality, holiday effects, and the lack of correlation with certain economic indicators. Understanding these patterns can help Walmart optimize its operations and marketing strategies to improve sales performance.

For further details, refer to the Jupyter Notebook file in this repository.
