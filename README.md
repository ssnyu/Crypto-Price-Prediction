# Cryptocurrency Price Prediction with Sentiment Analysis

## Overview

This repository contains the code implementation for the research paper titled "Cryptocurrency Price Prediction with Sentiment Analysis." The paper introduces a novel model that addresses limitations in existing works by incorporating sentiment analysis from various sources such as Twitter, Reddit, and CoinMarketCap news. The model leverages a robust deep learning architecture based on transformers for improved predictive capabilities.

## Key Features

- **Sentiment Integration:** The model incorporates sentiments from social media platforms and news sources, providing a more comprehensive analysis of factors influencing cryptocurrency prices.
- **Transformer-Based Architecture:** Utilizes a transformer-based neural network with encoder blocks for retaining context, uncovering complex patterns, and generating outputs of similar complexity.
- **Flexible Feature Configurations:** The code supports different feature configurations, allowing users to experiment with various combinations of Ethereum price, volume, sentiment data, and prices of correlated coins.

## Dataset

The dataset used for training spans approximately 730 days for Ethereum, with coin prices and volume data extracted from Yahoo Finance and sentiments collected from social media platforms.

## Experimentation

The experimental section explores the model's performance under different feature setups, ranging from a basic configuration using only Ethereum closing price data to a more comprehensive setup incorporating multiple dimensions.

## Results

The results showcase the model's performance metrics, including Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE), compared to other models such as LSTM, ANN, and MLP.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/cryptocurrency-price-prediction.git
   cd cryptocurrency-price-prediction
