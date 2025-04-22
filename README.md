This project implements a statistical arbitrage strategy for commodities using pairs trading. The focus is on identifying and exploiting mean-reverting behavior among closely related energy products such as Crude Oil (CL), Heating Oil (HO), and Gasoline (RB). The strategy integrates both quantitative signals and fundamental indicators from inventory data to generate high-conviction trading opportunities.

Pairs trading is a market-neutral strategy that profits from temporary divergence in the price relationship between two historically correlated assets. This project performs:

Cointegration & stationarity testing (ADF, Johansen)

Rolling beta estimation

Dynamic z-score thresholding for signal generation

Grid search optimization for entry/exit thresholds

Integration of EIA inventory data to improve signal quality

Performance backtesting and visualization of returns

