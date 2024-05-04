# Stock Data Analysis using yFinance and Sentiment Analysis

## Project Overview
- **Data Collection:** Using `yfinance` to fetch historical stock data.
- **Sentiment Analysis:** Analyzing news articles related to the stock using pre-trained models from Hugging Face's Transformers.
- **Data Visualization:** Plotting stock trends, daily and cumulative returns, and sentiment analysis results.
- **Statistical Analysis:** Using simple moving averages and other metrics to analyze stock price movements.

## Key Libraries Used
- `yfinance`: To fetch historical stock data.
- `transformers`: For running sentiment analysis models.
- `matplotlib`: For plotting graphs.
- `pandas`: For handling data in DataFrame format.
- `numpy`: To perform mathematical computations.

## Functions Developed

- **get_stock_data**: Fetches stock data for a specified period.
- **plot_stock_trend, plot_daily_returns, plot_cumulative_returns**: Various plotting functions for stock data visualization.
- **calc_returns**: Calculates daily returns from stock prices.
- **insights_stock_trend**: Generates insights from stock price trends and returns.
- **calc_simple_moving_average**: Computes moving averages for given window sizes.

## Example Analysis
The project includes analysis such as:
- Stock price trends and volatility analysis for BAC.
- Sentiment analysis on recent news articles about BAC using different NLP models.
- Impact of news sentiment on stock prices.

## Conclusion
This analysis demonstrates the potential of combining financial data with NLP to gain insights into stock behaviors. Such approaches can be instrumental for traders and analysts looking to enhance their market strategies.
