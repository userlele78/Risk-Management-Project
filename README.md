# Investment Portfolio Risk Management using BHS and Backtesting
**Project Overview**
This project provides a comprehensive analysis of Value at Risk (VaR), a widely used risk measure in finance for quantifying the maximum expected loss over a specific time frame at a given confidence level. The report focuses on applying parametric and non-parametric methods to evaluate the risks associated with a portfolio of two Vietnamese stocks: Vietnam Technological and Commercial Joint Stock Bank (TCB) and Agriculture Bank Insurance Joint Stock Corporation (ABI).

The primary goal of this analysis is to quantify the risk within the selected portfolio and evaluate the effectiveness of backtesting methods for VaR, particularly focusing on tail risk estimation.

[Link to Data of TCB Stock](https://finance.vietstock.vn/TCB/transaction-statistics.htm?grid=invest)<br />
[Link to Data of ABI Stock](https://finance.vietstock.vn/ABI/transaction-statistics.htm)

**Project Organization**
```
├── README.md          <- The top-level README for developers using this project.
├── Data
│   ├── merged_data-final         <- Data after merge close price of 2 stocks according to time
└── Code
    ├── non-parametric-VaR        <- Backtest and Historical Simulation for non-parametric approach
    └── parametric-VaR            <- Backtest and Historical Simulation for parametric approach
```

***Contents***

**Introduction**

- Overview of financial risk and the importance of VaR in risk management.
- Project scope, objectives, and expected outcomes.
- 
**Theoretical Background**

- Value at Risk (VaR): Explains parametric and non-parametric methods for VaR calculation.
- Backtesting: Techniques used to verify the accuracy of VaR estimates, including Unconditional and Conditional Coverage Tests.
  **Data**

- The analysis uses historical stock data of TCB and ABI, collected from the finance.vietstock.vn website.
- The data spans from May 4, 2023, to May 4, 2024, and includes daily closing prices.

**Tools and Methods Used**

- Parametric VaR Calculation: Analytical method based on mean and standard deviation of asset returns.
- Non-parametric VaR: Basic historical simulation using empirical percentiles of historical returns.
- Backtesting: Used to validate VaR models, employing the Kupiec Unconditional Coverage Test, Christoffersen Conditional Coverage Test, and Dynamic Quantile Test.
*Parametric VaR Calculation*

- Detailed calculation of portfolio VaR using the parametric method at a 99% confidence level.
- Calculation of the potential loss for TCB, ABI, and the total portfolio.
  *Basic Historical Simulation (Non-parametric VaR)*

- Detailed calculation using historical simulation to estimate portfolio VaR.
*Backtesting Results*

- Likelihood Ratio Framework and Dynamic Quantile Test results for backtesting VaR models.
- The report evaluates both parametric and non-parametric models based on backtest performance.
**Conclusion**

- Insights into the effectiveness of the VaR models in predicting risk within the chosen portfolio.
- Evaluation of backtesting methods and their role in financial risk assessment.

