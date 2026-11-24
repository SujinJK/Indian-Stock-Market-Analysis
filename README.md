# Indian Stock Market Analysis (Nifty 200)

Sector-level analysis of the companies in India's **Nifty 200** index.

## What I did
- Loaded the Nifty 200 constituent list and grouped every company by industry.
- Cleaned market-capitalisation values that mixed units (trillions and billions) into one consistent numeric scale.
- Ranked companies within each industry and produced a **top 5 by market cap per industry** table, exported to Excel (`top_5_industries.xlsx`).
- Visualised sector weightings with Matplotlib and Seaborn.

## Files
| File | Contents |
|---|---|
| `Nifty_50.ipynb` | Analysis notebook |
| `ind_nifty200list.csv` | Nifty 200 constituents with industry |
| `finance.xlsx` | Company market-cap data |
| `top_5_industries.xlsx` | Output: top 5 companies per industry |

**Tools:** Python, Pandas, Matplotlib, Seaborn, Excel
