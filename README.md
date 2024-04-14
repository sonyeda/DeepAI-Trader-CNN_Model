# DeepAI Trader - CNN Model

This repository hosts a project called DeepAI Trader, which utilizes a Convolutional Neural Network (CNN) model for stock market prediction and trading strategies.This model is a simple and plain work to predict kospi200 index futures prices based on convolutional neural networks. The project aims to predict stock price movements and make trading decisions based on historical price data and other relevant features extracted from financial markets.

## Dataset

Data was used since December, 2007, but I didn't separate data, so you can split it into training sets and test sets. Data was preprocessed with R. This data is essential for training and evaluating the CNN model for stock market prediction.

## Project Structure

The project structure is organized as follows:

- **data:** Contains the dataset used for training and testing the CNN model.
- **notebooks:** Includes Jupyter notebooks detailing the data preprocessing steps, feature engineering, model development, and evaluation.
- **src:** Contains the Python code for implementing the CNN model, backtesting trading strategies, and integrating with brokerage APIs for live trading.
- **reports:** Contains reports generated from the analysis, including visualizations, model performance metrics, and trading strategy results.

## Data Preprocessing and Feature Engineering

Data preprocessing involves cleaning and transforming the raw stock price data into a format suitable for training the CNN model. Feature engineering may include calculating technical indicators such as moving averages, relative strength index (RSI), or stochastic oscillators, which can provide additional insights into market trends and momentum.

## CNN Model for Stock Market Prediction

The core of the project is the CNN model designed to predict stock price movements based on historical data and other features. The CNN architecture is tailored to analyze sequential data such as time series, extracting patterns and trends that can help forecast future price movements. The model is trained on historical data and evaluated using appropriate metrics such as accuracy, mean squared error (MSE), or profitability metrics for trading strategies.

## Trading Strategies and Backtesting

The CNN model's predictions are used to develop trading strategies, including buy/sell signals and position sizing algorithms. These strategies are backtested using historical data to assess their performance and profitability. Various trading metrics such as Sharpe ratio, maximum drawdown, and annualized return are calculated to evaluate the effectiveness of the strategies.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `notebooks` directory to explore the Jupyter notebooks containing the analysis and modeling process.
3. Ensure you have the necessary dependencies installed. You can install them via pip using the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

4. Run the notebooks sequentially to replicate the analysis and understand the steps involved.

## Requirements

The project requires Python 3.11 along with various libraries. These dependencies are listed in the `requirements.txt` file.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

Customize this README according to your project's specific details and preferences.
