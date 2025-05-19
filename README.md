# Project Overview

This project aims to compare the returns of the traditional investment good  i.e. gold with the SP500. `Against Gold.pdf` (English) and `Altına Karşı.pdf` (Turkish) explains the details and the results of the project. 

* `Investment Strategy Analysis` is a jupyter notebook containing the code cells of the main analysis.

* `Supplemental Analyses for Main Research` is another jupyter notebook containing the codes of the supplementary work.

* `data.py`, `long_term_simulations`, `annual_calculations` contain the functions and the cpi data that were used in main analysis.

This project can be used for stock market returns analysis. By combining different trading strategies, one can compare good old buy-hold method with the more sophisticated ones.


# Setup

1. Clone the repository

```bash
git clone https://github.com/egonos/Against-Gold.git
cd Against-Gold
```

2. Create virtual environment
```bash
python -m venv venv
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

3. Install dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

After these steps, you can run the code inside the notebook files or Python scripts as needed.

# References

Resources of data:

1. 1950 to 2018 SP500 prices: https://www.kaggle.com/datasets/benjibb/sp500-since-1950/data
2. 2018 to 2024 SP500 prices: https://www.nasdaq.com/market-activity/index/spx/historical
3. CPI values of each year: https://www.minneapolisfed.org/about-us/monetary-policy/inflation-calculator/consumer-price-index-1913-
4. SPY Fund Prices: https://finance.yahoo.com/quote/SPY/history
5. SPY Dividend Amounts: https://www.nasdaq.com/market-activity/etf/spy/dividend-history
6. Gold Prices: https://stooq.com/q/d/?s=xauusd


Other References:

Adjusting money for inflation: 

* https://www.minneapolisfed.org/about-us/monetary-policy/inflation-calculator/consumer-price-index-1913-


Expense ratio & sales load:

* https://www.bankrate.com/investing/low-cost-index-funds-guide/
* https://www.bankrate.com/investing/what-is-an-expense-ratio/
* https://happay.com/blog/expense-ratio/

ETF Dividends: 

* https://www.investopedia.com/articles/investing/120415/how-dividendpaying-etfs-work.asp