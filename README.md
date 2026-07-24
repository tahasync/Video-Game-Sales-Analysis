# Video Game Sales Analysis — VGChartz 2024 EDA

An exploratory data analysis notebook on the VGChartz 2024 video game sales dataset (64,016 games) with 7 visualizations covering platform dominance, genre performance, critic score vs sales correlation, sales trends, top publishers, regional breakdown, and best-selling recent titles.

## What it does

Reads a real VGChartz dataset (included in the repo), cleans missing values and outlier records (drops games with >50M sales and rows missing critic scores — from 64K down to 4K records), then produces 7 matplotlib/seaborn visualizations with summary statistics. Pure descriptive analytics — no statistical modeling or ML.

## Tech stack

Python, pandas, matplotlib, seaborn, numpy, Jupyter

## Status

**Complete EDA exercise.** All 13 notebook cells execute successfully with real VGChartz data. The hardcoded absolute path in the `pd.read_csv()` call must be updated to run on another machine. Note: 93.5% of records are dropped during cleaning (mostly due to missing critic scores), reducing the dataset from 64K to 4K games — the critic_score column may be sparse.

## Contributors

- Muhammad Taha Naeem
- Abdur Rehman