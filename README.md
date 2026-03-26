# EEX Power Futures Midterm Project

This repository contains a Python-based coursework project built around EEX German power futures data. The work focuses on turning raw contract-level price data into a structured analysis pipeline covering descriptive statistics, volatility estimation, trading signal design, backtesting, and option pricing.

## What This Project Shows

- Cleaning and transforming futures data with pandas
- Handling contract rolls and building analysis-ready return series
- Distribution diagnostics with skewness, kurtosis, and Jarque-Bera tests
- Volatility forecasting with rolling-window estimators
- PnL analysis for outright and calendar-spread strategies
- Feature engineering for directional and relative-value signals
- Cross-sectional modeling with ridge regression
- Black-76 option pricing and hedge PnL decomposition

## Repository Contents

- `GRA6561_1026202.ipynb`: main notebook with the full analysis
- `GRA6561_1026202.pdf`: exported project report
- `midterm_presentation.pptx`: presentation slides
- `GRA65612_data.csv`: futures price dataset used in the notebook
- `figures/`: plots generated during the analysis

## Technical Stack

- Python 3.13
- pandas
- numpy
- matplotlib
- scipy
- Jupyter Notebook

## Selected Outputs

### Volatility Forecasting

![Volatility forecast](figures/vol.png)

### Outright vs Calendar Spread PnL

![PnL comparison](figures/1.4_pnl.png)

### Signal Backtest

![Signal backtest](figures/q21_pnl.png)

### Feature Correlation

![Feature correlation heatmap](figures/corr.png)

## Running The Notebook

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook GRA6561_1026202.ipynb
```

## Notes

This is a school project intended as a portfolio piece that demonstrates practical work in quantitative analysis, time-series modeling, and derivative pricing using Python.
