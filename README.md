# Netflix Movies and TV Shows — Exploratory Data Analysis

Exploratory analysis of Netflix's content catalog, looking at content type, genre mix, country of origin, and growth over time.

## Key Insights

- Movies make up roughly 70% of the catalog compared to TV Shows (6,126 vs. 2,664), suggesting Netflix's library is still primarily film-driven despite the platform's strong association with original series.
- Content additions grew almost exponentially from 2015 to 2019, then appear to drop in 2020-2021 — most likely a data collection artifact (the dataset was collected mid-2021), not a real decline.
- "International Movies" and "Dramas" are the two most common genres by a wide margin, pointing to Netflix's heavy investment in localized/international content.
- The United States dominates content origin by a large margin, followed by India and the UK, reflecting both Netflix's original production hubs and major licensing markets.
- Movie duration follows a roughly normal distribution centered around 90-100 minutes, with a long tail of a small number of much longer titles.

## Conclusion

Netflix's catalog is still predominantly movie-based, but the platform has clearly invested heavily in international content, with dramas and international titles leading by a wide margin. The apparent slowdown in 2020-2021 is most likely a data collection artifact rather than a real strategic shift — an important distinction when reporting trends from any dataset with a fixed collection date. With more time, it would be worth comparing this catalog composition against a competitor (e.g. Amazon Prime or Disney+) and analyzing ratings/maturity levels to understand audience targeting by region.

## Tools

Python, Pandas, Matplotlib, Seaborn

## Data

[Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) <!-- TODO: replace with the exact link if your version differs -->

## Notebook

See [`netflix_eda.ipynb`](./netflix_eda.ipynb) for the full analysis.
