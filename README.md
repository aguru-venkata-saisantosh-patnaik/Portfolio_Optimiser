Website Link: https://ravishankar2003.github.io/risk_based_portfolio_optimiser/

# Risk Based Portfolio Optimiser

## Overview

The Risk Based Portfolio Optimiser is a web-based tool designed to assist users in planning and optimizing their investments based on expected returns and risk levels. By inputting financial parameters such as initial investment, yearly investment, and rate of return, the tool calculates and visually represents the optimal asset allocation according to predefined risk profiles.

## Features

- **Asset Allocation Based on Risk Profiles:** Generates optimal portfolios across various risk levels (very low, low, medium, high, very high) by allocating investments in:
  - Bonds
  - Large-cap mutual funds
  - Mid-cap mutual funds
  - Small-cap mutual funds
  - Gold

- **Visual Representation:**
  - **Pie Chart:** Displays asset allocation corresponding to the user's expected total return.
  - **Stacked Bar Graph:** Shows total cumulative investment and total cumulative returns, with the x-axis representing the years and the y-axis showing total value of returns.
  - **Investment Table:** Provides detailed information including year, total cumulative investment, total cumulative return, and total portfolio value.

- **Icon:** A sleek favicon is included beside the website name in the browser tab for easy identification.

## Inputs

Users provide the following inputs:

1. **Starting Year:** The year the investment plan begins.
2. **Final Year:** The year the investment plan ends.
3. **Initial Investable Amount:** The amount available for investment in the starting year.
4. **Investable Amount Per Annum (IAPA):** The yearly investment amount.
5. **IAPA Increment:** The annual rate of increment for the investable amount.
6. **Expected Return:** The target total value of the investment by the final year.

## Calculation

The tool calculates potential returns across different risk profiles based on fixed allocation percentages to various asset classes, using the following assumed return rates:

- **Bond Return:** 6.5%
- **Large-cap Mutual Funds:** 10.7%
- **Mid-cap Mutual Funds:** 11.25%
- **Small-cap Mutual Funds:** 11.85%
- **Gold Return:** 9.3%

For each portfolio, the user's total investment growth is computed annually, considering allocation percentages, the rate of return of each asset class, and the IAPA increment. The risk profile is then evaluated based on the expected return.

## Risk Levels and Allocation

The tool provides four pre-defined portfolios (P1, P2, P3, P4) with varying allocation percentages for different asset classes. The portfolio with the lowest allocation to risky assets corresponds to the "very low" risk profile, while the one with the highest allocation corresponds to the "high" risk profile. The expected return is used to determine which portfolio aligns with the user’s risk tolerance.

## External References

- **Gold Return Forecast:** Traders Union Gold Forecast [https://tradersunion.com/currencies/forecast/gold/]
- **Mutual Fund Return Rates:**
  - Groww - Large, Mid, Small Cap Mutual Funds [https://groww.in/blog/large-cap-mid-cap-small-cap-do-you-know-the-difference]
  - CRISIL Report on Mutual Fund Returns [https://www.crisil.com/content/dam/crisil/our-analysis/reports/Research/documents/2021/07/shrinking-alpha.pdf]
  - Tickertape - Mutual Funds by Market Cap [https://www.statista.com/statistics/263617/gross-domestic-product-gdp-growth-rate-in-india/]
- **Bond Return Assumption:** Statista GDP Growth and Statista Inflation Rate [https://www.statista.com/statistics/271322/inflation-rate-in-india/]

## How It Works

1. **User Input:** Enter the required investment details.
2. **Calculation:** The tool uses predefined formulas to calculate potential growth and allocation of your portfolio based on historical return rates.
3. **Visual Output:** The results are displayed in a pie chart, stacked bar graph, and table format for easy analysis.

## Usage

1. Clone the repository.
2. Open the project in a web server environment.
3. Input the required values and analyze your results.

## Icon

A custom favicon symbolizing balance and informed investment decisions is included in the browser tab for easy identification of the website.

For any questions or contributions, please feel free to reach out!
