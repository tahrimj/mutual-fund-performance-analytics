Project: Mutual Fund Performance & Benchmark Validation

Objective
Build a reproducible pipeline to validate mutual fund NAV data, compute standardized performance metrics, and compare fund performance against an official benchmark.

Data Sources
- Mutual fund NAV data from AMFI (bulk 90-day files)
- NIFTY 50 Price Index data from NSE official website

Methodology
- Cleaned and standardized semi-structured NAV data
- Computed daily fund returns from NAV time series
- Integrated official benchmark data
- Calculated cumulative and excess returns
- Generated volatility and tracking error metrics

Quality Checks
- Date continuity validation
- Duplicate and missing NAV checks
- Abnormal return flagging

Assumptions & Limitations
- Benchmark uses price index, not TRI
- Short analysis window
- No expense ratio normalization

Tools
Python (pandas, matplotlib)

Steps to execute:
- Download Mutual fund NAV data from AMFI
- Download relevant libraries and run cells in nav.ipynb
- NIFTY 50 Price Index data from NSE official website
- Download relevant libraries and run cells in benchmark.ipynb
- Finally, download relevant libraries and run cells in compare.ipynb
