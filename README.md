This project leverages Brownian Motion and financial data to predict stock prices. It uses historical stock data retrieved in real-time and performs simulations to generate future price predictions. The application is built with a graphical user interface (GUI) using Tkinter for enhanced user interaction.

The tool also provides additional features like:

Confidence intervals for predictions
Bollinger Bands for technical analysis
Visualization of actual and predicted prices with confidence bounds
Exporting data and graphs to Excel for further analysis

Features

Real-time Stock Data Retrieval:
Fetch live stock price data using yfinance.
Analyze historical trends for prediction.
Stock Price Prediction:

Uses Brownian Motion for price forecasting.
Generates simulations and provides confidence intervals for predictions.
Normality Test:

Perform Shapiro-Wilk tests to determine the normality of stock returns.
Bollinger Bands:

Calculate and visualize Bollinger Bands to analyze price volatility.
Interactive GUI:

Developed using Tkinter for seamless user interaction.
Users can select the number of days for prediction and view results in multiple formats.
Graphical Visualization:

Plot historical prices, predicted values, and confidence intervals using matplotlib.
Data Export:

Save predicted prices and Bollinger Bands to Excel.
Automatically generates charts for easier interpretation.

How It Works
Input:
Users enter the stock ticker (e.g., AAPL, NFLX) and the start date for data retrieval.
Specify the number of days to predict future prices.

Prediction:
The application simulates multiple paths using Geometric Brownian Motion.
Computes statistical confidence intervals for price forecasts.

Visualization:
Displays predicted prices and graphs in the application window.
Users can export data to Excel with accompanying charts.

Additional Analysis:
Users can calculate and view Bollinger Bands for technical analysis.
