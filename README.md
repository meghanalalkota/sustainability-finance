 Project Description: Influence of sustainability and Financial Analysis of automobile industry
 Objective:
The primary objective of this project is to analyze and visualize key financial ratios for a selection of major automotive companies: BMW Group (BMWYY), Ford Motor Company (F), General Motors (GM), Toyota Motor Corporation (TM), and Tesla, Inc. (TSLA). By calculating and plotting these ratios, we aim to provide insights into the performance and volatility of these stocks over time.

Data:
The dataset used for this analysis includes daily stock prices and trading volumes for each of the selected companies. The stock price data consists of the following columns:
- Adjusted Close
- Close
- High
- Low
- Open
- Volume

 Financial Ratios Calculated:
1. **Daily Return**: The daily percentage change in the adjusted closing price.
2. **20-Day Simple Moving Average (SMA)**: The average closing price over the past 20 trading days.
3. **Volatility**: The standard deviation of daily returns over the past 20 trading days, which indicates the degree of variation in stock prices.
4. **Volume Weighted Average Price (VWAP)**: The average price at which the stock has traded throughout the day, weighted by trading volume.

Methodology:
1. **Data Preparation**:
   - Calculate the daily returns for each stock using the adjusted closing prices.
   - Compute the 20-day SMA for each stock using the closing prices.
   - Determine the volatility of each stock as the standard deviation of daily returns over the past 20 trading days.
   - Calculate the VWAP for each stock using the closing prices and trading volumes.

2. **Data Cleaning**:
   - Remove rows containing any NaN values to ensure clean and continuous data for analysis and visualization.

3. **Visualization**:
   - Create line plots for each financial ratio, showing how the ratio changes over time for each stock ticker.
   - Each plot includes a legend to differentiate between the stock tickers.

Results as of 06/04/24:
The visualizations produced by this analysis include:
- **Daily Return Plot**: Shows the day-to-day percentage changes in stock prices, highlighting short-term performance and volatility.
- **20-Day SMA Plot**: Illustrates the smoothed trend of stock prices over a 20-day period, helping to identify longer-term trends.
- **Volatility Plot**: Displays the fluctuation in stock prices over a 20-day window, providing insights into the stability or risk associated with each stock.
- **VWAP Plot**: Reflects the average trading price weighted by volume, useful for understanding the typical price level at which the stock is traded.

Conclusion:
This project provides a comprehensive analysis of key financial ratios for major automotive companies, offering valuable insights into their stock performance and market behavior. The visualizations enable easy comparison across different companies and time periods, helping investors and analysts make informed decisions.

The methodology used in this project can be applied to other stocks and financial ratios, making it a versatile tool for financial analysis and market research.
