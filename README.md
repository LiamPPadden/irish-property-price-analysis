# Irish Property Price Analysis (2010–2026)

An end-to-end data analysis project exploring trends in the Irish residential property market, using the Property Price Register (PPR) dataset.

## Overview

This project analyses 785,343 property transactions across Ireland from 2010 to 2026, examining how prices have moved over time, how they vary by county, and building a predictive model to forecast future price trends.

## Key Findings

- **National median price** rose from €202,000 (2010) to €365,000 (2026)
- **160.7% increase** in national median price since the 2013 post-crash low
- **Dublin** remains the most expensive county (median €350,000), while **Leitrim** is the most affordable (median €110,000)
- A linear regression model achieved an **R² score of 0.854**, explaining 85% of the variance in prices, and was used to forecast prices through 2030

## Tools & Techniques

- **Python** (pandas, NumPy, matplotlib, scikit-learn)
- Data cleaning and preprocessing of raw transaction-level data
- Exploratory data analysis and visualisation (price trends over time, county-level comparisons)
- Linear regression modelling for price prediction

## Visualisations

- `price_trend_ireland.png` — national price trend over time
- `price_trend_by_county.png` — price trends across counties
- `price_by_county.png` — median price comparison by county
- `price_prediction.png` — forecasted prices through 2030

## Notebook

See `analysis.ipynb` for the full analysis, including data cleaning steps, visualisations, and the predictive model.
