# BTC Trade

## Overview
This project implements a framework for an algorithmic trading model focused on Bitcoin (BTC). The backtesting period spans from **January 1, 2015, to December 31, 2017**. The model utilizes historical BTC price data to test the effectiveness of a trading strategy.

## Features
- 📈 Uses historical Bitcoin price data at a **15-minute interval**.
- 🛠 Implements a **trading strategy** and evaluates its performance.
- 📊 Provides **visualizations** for trade signals and portfolio performance.
- 🔄 Supports **backtesting** with data processing using `pandas` and `numpy`.

## Installation
To set up the environment and run the project, follow these steps:

### 1️⃣ Clone the repository:
```sh
git clone https://github.com/your-username/bitcoin-algo-trading.git
cd bitcoin-algo-trading
```

### 2️⃣ Install dependencies:
```sh
pip install -r requirements.txt
```

## Usage
### 📂 Ensure the dataset is available
Make sure you have the dataset (`btc_15m.csv`) in the appropriate directory.

### 📜 Run the Jupyter Notebook
```sh
jupyter notebook bitcoin-algo-trading-model.ipynb
```

Follow the notebook instructions to analyze the trading strategy.

## Dependencies
This project requires the following Python libraries:
- **Python 3.x**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

## Data Source
The project relies on `btc_15m.csv`, a dataset containing Bitcoin price data at a **15-minute interval**.

## Results
The notebook provides insights into the profitability and risk associated with the strategy, including:
- ✅ **Trade signals**
- 📉 **Portfolio performance over time**
- 📊 **Risk-adjusted returns**
