 Forecasting Net Prophet
## MercadoLibre Growth Analysis

### Overview

This project aims to analyze the financial and user data of MercadoLibre, the most popular e-commerce site in Latin America, to discover if the ability to predict search traffic can translate into successful stock trading. The project is divided into four main steps:

1. **Find unusual patterns in hourly Google search traffic**
2. **Mine the search traffic data for seasonality**
3. **Relate the search traffic to stock price patterns**
4. **Create a time series model with Prophet**

### Steps and Instructions

#### Step 1: Find Unusual Patterns in Hourly Google Search Traffic

1. **Load the Data**: Load the Google search traffic data from the `mercado_trends.csv` file.
2. **Visualize the Data**: Plot the data to identify any unusual patterns or anomalies.

    ![Unusual Patterns in Google Search Traffic](https://github.com/alghalia/Forecasting-Net-Prophet/blob/main/images/%201%20Unusual%20Patterns%20in%20Hourly%20Google%20Search%20Traffic.png)

3. **Analyze the Patterns**: Use statistical methods to detect any outliers or unusual patterns in the data.

#### Step 2: Mine the Search Traffic Data for Seasonality

1. **Group the Data**: Group the search traffic data by different time periods (hour, day of the week, week of the year).
2. **Plot the Data**: Create plots to visualize the average traffic by hour of the day, day of the week, and week of the year.

    ![Average Traffic by Hour](https://github.com/alghalia/Forecasting-Net-Prophet/blob/main/images/2.Average%20Traffic%20by%20Hour%20of%20the%20Day.png)
    
    ![Average Traffic by Day](https://github.com/alghalia/Forecasting-Net-Prophet/blob/main/images/3.Average%20Traffic%20by%20Day%20of%20the%20Week.png)
    
    ![Average Traffic by Week](https://github.com/alghalia/Forecasting-Net-Prophet/blob/main/images/4.Average%20trafic%20week%20of%20the%20year%20.png)

3. **Analyze Seasonality**: Identify any seasonal patterns in the search traffic data.

#### Step 3: Relate the Search Traffic to Stock Price Patterns

1. **Load the Stock Data**: Load the stock price data from the `mercado_stock_price.csv` file.
2. **Concatenate DataFrames**: Combine the stock price data with the search traffic data.
3. **Analyze Relationships**: Use correlation analysis and other statistical methods to find relationships between search traffic and stock prices.

    ![Search Traffic vs Stock Prices](https://github.com/alghalia/Forecasting-Net-Prophet/blob/main/images/5.Search%20Traffic%20vs.%20Stock%20Prices.jpg)

#### Step 4: Create a Time Series Model with Prophet

1. **Prepare the Data**: Format the data for use with the Prophet forecasting model.
2. **Build the Model**: Create and fit a time series forecasting model using Prophet.
3. **Evaluate the Model**: Assess the model's performance and use it to make future predictions.

   ![Time Series Forecast with Prophet](https://github.com/alghalia/Forecasting-Net-Prophet/blob/main/images/forcasting%20the%20net%20prophet.png)


### Dependencies

- pandas
- numpy
- matplotlib
- hvplot
- prophet

### Acknowledgments

- MercadoLibre for the data
- Prophet for the time series forecasting library
