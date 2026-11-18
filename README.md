# Stock Risk & Return Dashboard

An interactive 2-page Power BI dashboard comparing five US stocks and the S&P 500 on return and risk, January 2021 – November 2026.

**Stocks:** Apple, Coca-Cola, ExxonMobil, JPMorgan, Microsoft, and S&P 500 (SPY) as benchmark.

## Pages
- **Overview:** growth of $100, risk vs return scatter, Sharpe ratio ranking, key findings.
- **Risk Analysis:** drawdown from peak, summary statistics table (total return, CAGR, volatility, Sharpe ratio, max drawdown, beta).

## Metrics (DAX measures)
- Total return and CAGR
- Annualized volatility
- Sharpe ratio (risk-free rate = 4%)
- Maximum drawdown
- Beta vs S&P 500

## Key findings
- ExxonMobil had the strongest result (405% total return, 31.8% CAGR) and the best Sharpe ratio (1.02).
- Microsoft had the weakest Sharpe ratio (0.47).
- Coca-Cola was the most defensive stock (volatility 16.5%, beta 0.26).
- JPMorgan had the deepest drawdown (-38.8%).

## Data
Stooq, adjusted close prices (dividends included).

## Files
- `Stock_Dashboard_v1..pbix`: Power BI file (download and open in Power BI Desktop to use the slicers)
- `Stock_Data_for_PowerBI_Final.xlsx`: cleaned price data used in the dashboard

## Note
Learning project, not investment advice.
