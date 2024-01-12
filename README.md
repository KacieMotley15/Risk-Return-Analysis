# Analyzing Portfolio Risk and Return

## Overview

In this challenge, the objective is to analyze the risk and return of four investment options for inclusion in client portfolios. The data includes daily returns, standard deviations, Sharpe ratios, and betas. The analysis involves evaluating performance, volatility, risk profile, and overall risk-return profile of each portfolio.

## Instructions

### 1. Import the Data

- Import the required libraries and dependencies.
- Use the `read_csv` function and `Path` module to read the `whale_navs.csv` file into a Pandas DataFrame, creating a DateTimeIndex.
- Use the `pct_change` function to create the daily returns DataFrame based on NAV prices and the closing price of the S&P 500 Index.

### 2. Analyze the Performance

- Visualize daily return data of the four fund portfolios and the S&P 500 using the default Pandas plot function.
- Calculate cumulative returns for the four fund portfolios and the S&P 500 using the `cumprod` function.
- Visualize cumulative return values for the four funds and the S&P 500 over time using the default Pandas plot.

### 3. Analyze the Volatility

- Visualize daily return data for each portfolio and the S&P 500 using box plots.
- Create a new DataFrame containing data for just the four fund portfolios and visualize daily return data for these portfolios using a box plot.

### 4. Analyze the Risk

- Calculate and review the standard deviation for each portfolio and the S&P 500.
- Calculate annualized standard deviation for each portfolio and the S&P 500.
- Plot rolling standard deviations using a 21-day window for both all portfolios and only the four fund portfolios.
- Answer questions based on the standard deviation and rolling metrics.

### 5. Analyze the Risk-Return Profile

- Calculate annualized average return data and Sharpe ratios for each portfolio and the S&P 500.
- Visualize Sharpe ratios for all portfolios and the S&P 500 in a bar chart.

### 6. Diversify the Portfolio

- Calculate variance of the S&P 500 using a 60-day rolling window and visualize the last five rows.
- For two chosen portfolios, calculate covariance, beta, and plot the 60-day rolling beta.
- Answer questions based on the sensitivity to movements in the S&P 500 and recommend portfolios for inclusion.

## Usage

Provide instructions or examples on how to use or replicate the analysis locally.

## Contributing

If you'd like to contribute to the project, follow the guidelines outlined in the CONTRIBUTING.md file.

## License

This project is licensed under the [License Name] - see the [LICENSE.md](LICENSE.md) file for details.
