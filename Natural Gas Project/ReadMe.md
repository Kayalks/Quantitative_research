# Natural Gas Pricing Strategy
**Investigate and Analyze Price Data**

Objectives:
- Analyze historical price data of natural gas from October 2020 to September 2024.
- Extrapolate future prices for an additional year, considering seasonal trends.
- Estimate gas prices on any given date, based on historical trends and seasonal patterns.

Implementation:
- Data Collection: Natural gas prices at the end of each month (October 2020 to September 2024) were obtained from an external market data provider.
- Data Analysis: Performed exploratory data analysis (EDA) to identify seasonal trends and patterns in the prices.
- Extrapolation: Used statistical methods (such as ARIMA or moving averages) to extrapolate prices for the next year.
- Visualization: Created visualizations to display price trends, identify seasonality, and highlight fluctuations.

Insights & Results
- Seasonality: Identified that natural gas prices exhibit seasonal trends, with higher prices during the winter months.
- Extrapolation: Successfully extrapolated prices for the next year with reasonable accuracy, providing useful estimates for trading contracts.

**Price a Commodity Storage Contract**

Objectives:
- Develop a pricing model for a natural gas storage contract, considering injection and withdrawal dates, storage costs, and the prices at which the commodity can be bought and sold.
- Calculate the value of the contract based on the price differential, storage fees, and other associated costs.

Implementation:
- Input Parameters: The model accepts input parameters such as:
    - Injection and withdrawal dates
    - Prices at those dates
    - Storage fees and other costs (e.g., transportation, injection/withdrawal costs)
- Contract Valuation: The model calculates the value of the contract by estimating the difference between the selling and buying prices, adjusting for any associated costs.
- Output: Returns the net value of the contract, which can help the trading desk make informed decisions.

Insights & Results
- Valuation: The pricing model successfully estimates the contract's value, factoring in storage costs, transportation, and other variables, providing a clear view of potential profits or losses.
