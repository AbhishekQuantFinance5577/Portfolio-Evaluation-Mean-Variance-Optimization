# Portfolio_Evaluation_-_Optimization
This project evaluates and optimizes various investment portfolios using Python to determine the best option for a risk-averse investor. It compares risk-return trade-offs and mean-variance efficiency of different portfolio strategies.


### Project Description: Portfolio Evaluation and Optimization for Risk-Averse Investors

#### Purpose
The project had two main goals:
1. To evaluate and compare the risk-return trade-offs of different investment portfolios using Python.
2. To optimize portfolios for a risk-averse investor seeking a mean-variance efficient portfolio.

#### Assignment
The objective was to determine which of the following portfolios is the best investment for an investor with average risk aversion:
1. **All-Equity Portfolio:** 100% invested in equity.
2. **Traditional 60/40 Portfolio:** 
   - 60% equity
   - 40% intermediate Treasury bonds
3. **Harry Browne’s Permanent Portfolio:** 
   - 25% equity
   - 25% long-term Treasury bonds
   - 25% Treasury bills (cash)
   - 25% gold
4. **Ray Dalio’s All Seasons Portfolio:**
   - 30% equity
   - 40% long-term Treasury bonds
   - 15% intermediate Treasury bonds
   - 7.5% commodities
   - 7.5% gold
5. **Custom Portfolio:** Built using asset class returns from histretSP.csv.

#### Implementation Details
1. **Data Source:** Used asset class returns from histretSP.csv, which includes:
   - S&P 500 annual returns for equity.
   - T-Bill annual returns for 3-month Treasury bills.
   - T-bond annual returns for 10-year Treasury bonds.
   - Baa bond annual returns for Moody’s Baa corporate bonds.
   - Real estate annual returns for residential real estate.
   - Gold annual returns for gold (commodities).
2. **Analysis:**
   - Calculated and compared the risk and return metrics of each portfolio.
   - Assessed the mean-variance efficiency of the portfolios.
   - Evaluated the pros and cons of each asset class within the portfolios.
3. **Optimization:**
   - Optimized each portfolio to achieve mean-variance efficiency.
4. **Recommendations:**
   - Provided a detailed explanation of the best portfolio for a risk-averse investor.
   - Discussed the limitations and potential improvements for each portfolio.

#### Key Metrics Evaluated:
- **Total Return:** The overall gain or loss on the investment.
- **Annualized Return:** The geometric average amount of money earned by an investment each year over a given time period.
- **Volatility:** The degree of variation of trading prices.
- **Sharpe Ratio:** A measure of risk-adjusted return.
- **Maximum Drawdown:** The maximum observed loss from a peak to a trough.

#### Outcomes
- Conducted a comprehensive comparison of different investment portfolios based on historical data.
- Gained insights into the risk-return trade-offs and efficiency of each portfolio.
- Provided clear recommendations for the best investment strategy tailored for a risk-averse investor, understanding the limitations and areas for potential improvement.
