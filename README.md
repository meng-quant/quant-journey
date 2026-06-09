# Quant Journey — Market Analysis Project

## Overview
A 5-day hands-on quantitative analysis of US and Singapore equity markets 
using Python. Built as part of my preparation for MQF at SMU Singapore.

## What I Built
- Downloaded and analysed 250 days of real SPY (S&P 500) and STI ETF market data
- Calculated daily returns, cumulative returns, volatility and Sharpe ratio
- Identified the two most extreme market days in 2025 (April 4 and April 9) 
  and connected them to the US-China tariff war
- Compared return distributions against Gaussian — found kurtosis of 23.5, 
  confirming significant fat tails in real market data
- Discovered SPY-STI lead-lag relationship: 0.61 lagged correlation vs 
  -0.09 same-day correlation, explained by timezone difference
- Found STI outperformed SPY in 2025: 29% vs 11% return, 
  Sharpe 1.96 vs 0.63
- ![SPY RIsk Dashboard](SPY_risk_dashboard.png)
- Priced a European call option using Monte Carlo simulation 
  (risk-neutral pricing) - matched Black-Scholes within $0.95
- Built call option payoff diagram showing breakeven at $758.78,
  max loss $58.78, unlimited upside

## Tools
Python, Jupyter, yfinance, pandas, numpy, matplotlib

## Key Finding
STI delivered superior risk-adjusted returns in 2025 due to lower direct 
exposure to US-China tariff war. SPY volatility of 19.45% vs STI 13.63% 
explains the Sharpe ratio gap despite STI's higher absolute return.

## Status
Week 1 complete: SPY/STI risk analysis, VaR, CVaR, rolling volatility
Week 2 in progress: Monte Carlo simulation, options pricing
