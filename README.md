# Kaggle Stock Walk-Forward ML

## TL;DR
Builds and evaluates ML models for stock prediction using proper time-series walk-forward validation.

## Why this matters
- Showcases time-series discipline (no leakage), feature engineering, and robust evaluation
- SQL/Python + modeling + reporting skills in one repo
- Reproducible baseline → ablation-ready

## Approach (draft)
- Select Kaggle dataset (prices + fundamentals)
- Engineer lag/rolling features; target = next-day/next-week returns
- Walk-forward splits (train → validate → roll)
- Compare baselines (LR, RF/XGB, simple LSTM) with consistent metrics

## Roadmap
- [ ] Dataset selection + EDA
- [ ] Walk-forward splitter utility
- [ ] Baseline models + metrics
- [ ] Model comparison report + charts
