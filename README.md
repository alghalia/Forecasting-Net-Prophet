# Forecasting-Net-Prophet
# MercadoLibre Growth Analysis

## Overview

This project aims to analyze the financial and user data of MercadoLibre, the most popular e-commerce site in Latin America, to discover if the ability to predict search traffic can translate into successful stock trading. The project is divided into four main steps:

1. **Find unusual patterns in hourly Google search traffic**
2. **Mine the search traffic data for seasonality**
3. **Relate the search traffic to stock price patterns**
4. **Create a time series model with Prophet**


## Steps and Instructions

### Step 1: Find Unusual Patterns in Hourly Google Search Traffic

1. **Load the Data**: Load the Google search traffic data from the mercado_trends.csv file.
2. **Visualize the Data**: Plot the data to identify any unusual patterns or anomalies.

    ![Unusual Patterns in Google Search Traffic](path/to/graph1.png)

3. **Analyze the Patterns**: Use statistical methods to detect any outliers or unusual patterns in the data.

### Step 2: Mine the Search Traffic Data for Seasonality

1. **Group the Data**: Group the search traffic data by different time periods (hour, day of the week, week of the year).
2. **Plot the Data**: Create plots to visualize the average traffic by hour of the day, day of the week, and week of the year.

    ![Average Traffic by Hour](path/to/graph2.png)
    
    ![Average Traffic by Day](path/to/graph3.png)
    
    ![Average Traffic by Week](path/to/graph4.png)

3. **Analyze Seasonality**: Identify any seasonal patterns in the search traffic data.

### Step 3: Relate the Search Traffic to Stock Price Patterns

1. **Load the Stock Data**: Load the stock price data from the mercado_stock_price.csv file.
2. **Concatenate DataFrames**: Combine the stock price data with the search traffic data.
3. **Analyze Relationships**: Use correlation analysis and other statistical methods to find relationships between search traffic and stock prices.

    ![Search Traffic vs Stock Prices](path/to/graph5.png)

### Step 4: Create a Time Series Model with Prophet

1. **Prepare the Data**: Format the data for use with the Prophet forecasting model.
2. **Build the Model**: Create and fit a time series forecasting model using Prophet.
3. **Evaluate the Model**: Assess the model's performance and use it to make future predictions.

    ![Time Series Forecast with Prophet](path/to/graph6.png)


## Dependencies

- pandas
- numpy
- matplotlib
- hvplot
- prophet

## Acknowledgments

- MercadoLibre for the data
- Prophet for the time series forecasting library
