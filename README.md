# Stock Price Prediction with Polynomail Regression

This program predicts future stock prices using Polynomail  regression. It takes historical stock price data from a CSV file and forecasts the next 30 days of stock prices.

## Features

- Loads historical stock price data from a CSV file.
- Prepares the data for linear regression modeling.
- Trains a linear regression model to predict future stock prices.
- Generates predictions for the next 30 days.
- Plots the actual and predicted stock prices.
- Prints the predicted stock prices for the next 30 days.

## Requirements

- Python 3.7 or higher
- pandas
- numpy
- matplotlib
- scikit-learn

## Installation

1. Clone the repository or download the script file.

2. Install the required Python packages:
    ```bash
    pip install pandas numpy matplotlib scikit-learn
    ```

## Usage

1. Prepare your CSV file with at least two columns: `Date` and `Close`. The `Date` column should contain the dates of the stock prices, and the `Close` column should contain the closing prices of the stock.

2. Update the `csv_file` variable in the script with the path to your CSV file:
    ```python
    csv_file = "your_stock_data.csv"  # Replace with your CSV file path
    ```

3. Run the script:
    ```bash
    python stock_price_prediction.py
    ```

4. The script will output the Mean Squared Error of the model and print the predicted stock prices for the next 30 days.

5. The script will also display a plot comparing the actual closing prices with the predicted prices for the next 30 days.

## Example

Here is an example of what the CSV file should look like:

```csv
Date,Close
2020-01-01,300.35
2020-01-02,302.56
2020-01-03,298.44
...
