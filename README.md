# How did Italian banks react to ECB rate decisions?

Event study on 6 Italian listed banks (Intesa Sanpaolo, UniCredit, Banco BPM,
BPER, MPS, Mediobanca) around ECB monetary policy meetings, July 2022 – 2025.

## Question
Do Italian bank stocks outperform or underperform the market (FTSE MIB)
around ECB rate hikes, cuts and holds?

## Method (planned)
- Daily prices via `yfinance`; ECB decision dates from the official ECB website
- Abnormal return = bank return − FTSE MIB return
- Cumulative abnormal return in a [-1, +1] day window around each decision
- Comparison by decision type and by bank; events close to M&A news flagged

## Status
🚧 Work in progress — expected completion: November 2026

## Tools
Python · pandas · yfinance · matplotlib · Google Colab
