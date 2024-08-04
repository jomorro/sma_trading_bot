# Moving Average Trading Strategy
## Overview

This project implements a moving average trading strategy to analyze and trade stocks using Python. The strategy leverages simple moving averages (SMA) to generate buy and sell signals based on stock price trends. The project uses pandas for data manipulation, Matplotlib for visualization, yFinance for fetching stock data, and NumPy for numerical operations.
## Features

* Fetch historical stock data using the yFinance API
* Compute moving averages and generate trading signals
* Analyze and visualize trading strategy performance
* Plot stock prices, moving averages, and trading signals

## Prerequisites

* Python 3.7 or higher
* pip (Python package installer)

## Installation

1. Clone the repository:

        git clone https://github.com/yourusername/sma_trading_bot.git

2. Navigate to the project directory:

        cd sma_trading_bot

3. Create a virtual environment (optional but recommended):

         python -m venv venv

4. Activate the virtual environment:

        Windows: venv\Scripts\activate

        MacOS/Linux: source venv/bin/activate

5. Install the required packages:

       pip install -r requirements.txt

## Data

* Stock Data: The project fetches historical stock data using the yFinance library. No additional data files are required as the data is pulled directly from Yahoo Finance.
