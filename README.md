Stock Trend Prediction with News Sentiment Analysis
This project uses machine learning and sentiment analysis to predict stock trends. By leveraging historical stock price data and analyzing news sentiment, the system provides stock predictions along with insights based on the current market sentiment from news sources.

Features
Stock Trend Prediction: Using historical stock data, a machine learning model predicts future stock prices.
News Sentiment Analysis: The application fetches recent news articles for the given stock ticker and analyzes the sentiment, providing insights into how the news might affect the stock price.
Interactive Dashboard: Built with Streamlit for an interactive and user-friendly experience.
Visualization: Includes visualizations of the stock's historical prices, moving averages, and the model's predicted vs actual prices.
Key Components
Stock Data: Uses the Yahoo Finance API to fetch historical stock prices.
Sentiment Analysis: Uses the VADER Sentiment Analysis library to analyze the sentiment of news articles related to the stock.
Machine Learning: A deep learning model built using Keras to predict future stock prices based on historical data.
News API: Fetches the latest news articles related to the stock ticker using NewsAPI.
