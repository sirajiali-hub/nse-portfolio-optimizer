# NSE Halal Portfolio Optimizer

**In one line:** Showing how to split money between Sharia compliant NSE shares to get the best return for the risk taken.

## The question
If an investor can only hold a few compliant shares, how much should go into each to balance return and risk?

## What I did
1. Picked five shares: Safaricom, KenGen, Bamburi, Kenya Power and Sasini.
2. Measured each share's return and how much its price swings.
3. Tried 10,000 random ways of splitting the money between them.
4. Found two useful mixes: the one with the best return for its risk, and the one with the lowest risk.

## What I found
* **Lowest risk mix:** Safaricom is the anchor at 39%, because its price swings the least.
* **Spreading money across shares** that do not move together lowers overall risk.

## Important note on the data
Only Safaricom uses real price data. The other four shares use **simulated prices**, because free historical NSE data is hard to get. This project shows the **method**, not real investment results. The return figures should not be read as what an investor would have earned.

## Next step
Rerun with real prices for all five shares, and test the mix on a later period it was not built on.

## Files
* `portfolio_analysis.ipynb`: the full analysis

## How to run
1. Run `pip install pandas numpy matplotlib seaborn`
2. Open the notebook and run all cells from the top.

**Tools:** Python
