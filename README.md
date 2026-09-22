# Forward-looking Hierarchical risk parity cryptocurrency portfolio
Utilizing GARCH-LSTM volatility forecasting and GNN correlation prediction

Research Objectives:
This study develops a forward-looking Hierarchical Risk Parity (HRP) framework for cryptocurrency portfolio optimisation by integrating econometric and machine-learning techniques for dynamic risk forecasting. Using a portfolio of 24 cryptocurrencies, a Student-t GARCH(1,1) model is first employed as the baseline volatility model, followed by a Long Short-Term Memory (LSTM) network to forecast seven-day-ahead 30-day realised volatility. A Graph Neural Network (GNN) is subsequently applied to forecast the corresponding 30-day cross-asset correlation structure. The predicted volatility and correlation estimates are combined to construct a forward-looking covariance matrix, which is incorporated into HRP to determine portfolio weights. The proposed GARCH–LSTM–GNN–HRP framework is evaluated against Traditional HRP, GARCH-HRP, LSTM-HRP, Equal Weight, Inverse Volatility, and Minimum Variance portfolios using a genuinely unseen out-of-sample period. 

Sample data:
In-sample: 1 January, 2021 – 30 June, 2026
Out-of-sample: 1 July, 2026 – 15 August, 2026

Data Source: Yahoo! Finance, CoinMarketCap
