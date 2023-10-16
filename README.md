# Mid_Cap_Crypto Analysis Script

This script is designed to gather and analyze historical trading data from Binance in order to select an optimal cryptocurrency on which to run a market-making bot.

## Overview

The script performs the following main functions:

1. **Fetching Order Book Depth**: Retrieves the current state of the order book for a specified cryptocurrency pair from Binance.
2. **Gathering Historical Data**: Collects historical price and trading volume data for a given cryptocurrency pair.
3. **Structuring Order Book Data**: Processes raw order book data to generate meaningful insights.
4. **Analyzing Order Book in USDT**: Calculates parameters like bid-ask spread, order book depth, and order book imbalance in USDT for each cryptocurrency pair.
5. **Fetching Recent Trades**: Collects data about recent trades for each cryptocurrency pair.
6. **Calculating Trade Volumes**: Computes the total trade volume for each cryptocurrency pair.
7. **Getting Historical Data with Binance Client**: Uses the Binance API client to gather historical candlestick data.
8. **Processing and Analyzing Historical Data**: Calculates statistics like average daily trading volume and volatility over different time horizons (1 month, 6 months, 1 year).

## Usage

To utilize this script, ensure you have the required Python libraries installed and you've set up the necessary API keys.

## Note

This script focuses on data analysis and does not execute any trades. It provides valuable insights which can be used to make informed trading decisions, especially when deciding which cryptocurrency pair to target for market-making activities.

## Disclaimer

This script is intended for educational and informational purposes only. Ensure to test any trading strategies in a sandbox environment before deploying with real funds.
