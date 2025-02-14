This Google Colab notebook contains a Python script that simulates various trading strategies using historical stock data. The simulation allows users to choose from different strategies and visualize their performance over time.

## Features

- **Multiple Trading Strategies**: Choose from six different trading strategies, including Moving Average Crossover, RSI Stochastic, Fibonacci Retracement, Bollinger Bands, MACD Crossover, and ATR-Based Volatility.
- **Monte Carlo Simulation**: Simulate multiple price paths to evaluate the performance of each strategy.
- **User Input**: Enter a stock ticker symbol and select a trading strategy to run the simulation.
- **Visualization**: Plot the simulated price paths and moving averages to visualize the strategy's performance.

## Requirements

- Python 3.7 or later
- Required Python packages:
  - numpy
  - pandas
  - matplotlib
  - yfinance
  - ta (Technical Analysis Library)

You can install the required packages using pip:

```bash
pip install numpy pandas matplotlib yfinance ta
```

## Usage

1. **Open the Notebook**:
   - Open this notebook in Google Colab by clicking on the provided link or by uploading it to your Google Colab environment.

2. **Run the Simulation**:
   - Execute the cells in the notebook to run the simulation.
   - When prompted, enter the stock ticker symbol (e.g., AAPL for Apple Inc.).
   - Choose a trading strategy by entering the corresponding number.

3. **View Results**:
   - The script will output the highest win, worst loss, and average performance of the selected strategy.
   - A plot of the simulated price paths will be displayed.

## Strategies

1. **Moving Average Crossover**: Generates signals based on the crossover of short-term and long-term moving averages.
2. **RSI Stochastic**: Combines the Relative Strength Index (RSI) and Stochastic Oscillator to generate trading signals.
3. **Fibonacci Retracement**: Uses Fibonacci levels to identify potential support and resistance levels.
4. **Bollinger Bands**: Generates signals based on price volatility relative to a moving average.
5. **MACD Crossover**: Uses the Moving Average Convergence Divergence (MACD) indicator to generate trading signals.
6. **ATR-Based Volatility**: Uses the Average True Range (ATR) to generate signals based on price volatility.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the open-source community for the libraries and tools used in this project.
- Special thanks to the contributors and maintainers of the `yfinance` and `ta` libraries.
