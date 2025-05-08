
# Analyzing Ticker Trends

This project is designed to analyze stock ticker trends using various financial and technical indicators, including Moving Average Convergence Divergence (MACD), Relative Strength Index (RSI), and predictive modeling using Facebook's Prophet library.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [File Structure](#file-structure)
- [Results](#results)
- [License](#license)

---

## Overview

This project provides a comprehensive approach to analyzing stock price trends using Python. By leveraging popular libraries like `yfinance`, `Prophet`, and `matplotlib`, it enables users to visualize, analyze, and predict stock prices over various timeframes.

### Goals:
- Fetch historical stock data.
- Calculate and visualize technical indicators (MACD, RSI).
- Generate predictions for future price trends using the Prophet forecasting model.

---

## Features

1. **Data Retrieval**:
   - Fetch historical stock price data for a specified symbol using `yfinance`.

2. **Technical Analysis**:
   - Calculate and visualize:
     - MACD (Moving Average Convergence Divergence) and Signal Lines.
     - RSI (Relative Strength Index).

3. **Predictive Modeling**:
   - Train a model using Prophet to forecast future stock prices.

4. **Visualization**:
   - Plot and analyze trends across different timeframes (weekly, monthly, quarterly).

---

## Installation

### Prerequisites:
- Python 3.8 or later
- Jupyter Notebook (recommended for running the `.ipynb` file)

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/goodtam8/Analyzing-Ticker-Trends.git
   cd Analyzing-Ticker-Trends
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Open the Jupyter Notebook file:
   ```bash
   jupyter notebook "project (1) (2) (1).ipynb"
   ```

2. Follow the task sections in the notebook:
   - **Task 0a**: Import necessary libraries.
   - **Task 0b**: Fetch historical stock data.
   - **Task 1a-c**: Calculate and visualize MACD and Signal Line.
   - **Task 2a-b**: Calculate and visualize RSI.
   - **Task 3a-b**: Train and predict stock prices using Prophet.

3. Modify the stock symbol (e.g., `AAPL`, `BTC-USD`) or the analysis period as needed.

---

## Dependencies

The project uses the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `plotly`
- `yfinance`
- `nltk`
- `prophet`
- `textblob`
- `requests`

All dependencies can be installed via `pip install -r requirements.txt`.

---

## File Structure

Here is a brief overview of the repository structure:

```
Analyzing-Ticker-Trends/
├── project (1) (2) (1).ipynb  # Main Jupyter Notebook
├── README.md                  # Project documentation
└── requirements.txt           # List of dependencies
```

---

## Results

### Visualizations:
1. **MACD and Signal Line**:
   - Visualize trends and crossovers for different timeframes (daily, weekly, monthly, quarterly).

2. **RSI**:
   - Identify overbought and oversold conditions using RSI.

3. **Stock Price Forecast**:
   - Predict and visualize future stock prices using Prophet.

### Example Plots:
- MACD and Signal Line for `AAPL`.
- RSI for `AAPL`.
- Predicted stock prices for `AAPL`.

---

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute this project as per the terms of the license.

---

### Author

Developed by [goodtam8](https://github.com/goodtam8).
```

