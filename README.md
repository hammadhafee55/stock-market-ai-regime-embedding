stock-market-ai-regime-embedding

Stock Market AI Regime Embedding System

This project is an artificial intelligence based stock market analysis system that uses t SNE and UMAP for visualizing market behavior, KMeans clustering for detecting market regimes, LSTM for price prediction, and a DQN style agent for simulating trading decisions. It converts raw stock data into meaningful patterns for understanding, predicting, and simulating market movements.

Overview

This project builds an end to end machine learning and deep learning pipeline for financial data analysis. It helps discover hidden structures in the stock market by combining unsupervised learning, deep learning, and reinforcement learning techniques. The goal is to understand how markets behave rather than just predicting prices.

Key Features

The system performs feature engineering on stock market data including price, volume, returns, moving averages, volatility, and momentum. It reduces high dimensional data into two dimensional visual space using t SNE and UMAP. It then groups similar market conditions using KMeans clustering to identify different market regimes such as bullish, bearish, and sideways behavior. It also trains an LSTM model for predicting future prices and simulates trading decisions using a reinforcement learning inspired agent.

Dataset Requirements

The dataset should include open, high, low, close, volume, return, moving average values, volatility, and momentum features. Missing values are handled during preprocessing and all features are scaled before training.

Methodology

First the raw market data is cleaned and prepared. Then technical indicators are created to represent market behavior more effectively. After that dimensionality reduction techniques are applied to visualize hidden structures in the data. Clustering is used to identify market states. A deep learning model is trained to predict price movements. Finally a trading simulation environment is used to test decision making using buy sell and hold actions.

Model Components

The project uses KMeans clustering for unsupervised learning, t SNE and UMAP for visualization, LSTM neural networks for time series forecasting, and a simple reinforcement learning style agent for trading simulation.

Output Insights

The system helps visualize market behavior, detect hidden patterns, predict future prices, and simulate trading strategies based on learned patterns.

Future Improvements

Future versions can include real time market data integration, advanced reinforcement learning models, transformer based forecasting, portfolio optimization, and risk management systems.
