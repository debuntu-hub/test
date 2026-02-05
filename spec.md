# Backtest Platform SPEC

## Purpose
- Reproducible backtest environment
- Works on local / Codespaces / GitHub Actions
- Large-scale data support

## Tech Stack
- Python 3.11
- DuckDB
- Parquet
- pandas / numpy

## Data Policy
- No raw CSV in Git
- Data is always reproducible
- DuckDB file is generated, not stored

## Markets
- JP Stocks (J-Quants)
- FX (USDJPY first)
