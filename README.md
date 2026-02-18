# Macro Bond Timing via Recession Probability

## Research Question
Can recession probability predicted by yield spread improve bond allocation timing?

## Data
- 10Y-2Y Treasury yield spread
- NBER recession indicator
- 10Y Treasury return (duration approximation)
- Monthly data, 1990–2025

## Methodology
1. Logistic regression predicting recession probability (12M ahead)
2. Regime classification (High vs Low recession probability)
3. Bond timing strategy based on predicted regime
4. Backtest and performance comparison vs Buy & Hold

## Key Results
- Logistic regression AUC: 0.89
- High recession regime: higher bond returns
- Regime-based allocation improves drawdown control
- Continuous allocation improves stability

## Conclusion
Yield spread contains predictive information for bond returns through recession channel.

## Future Improvements
- Out-of-sample rolling estimation
- Transaction cost modeling
- Multi-factor macro extension
