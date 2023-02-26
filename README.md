# Building a Crypto Trading Dashboard – The First Steps

This project relates to a blog post linked [here](https://nate23424533.wordpress.com/2022/12/05/building-a-crypto-trading-dashboard-the-first-steps/).  The blog post details my efforts to begin a crypto trading dashboard application using the skills I learned in Phase 1 of the Flatiron School's Data Science course to collect and begin analyzing historical trading activity of a cryptocurrency.  

The Jupyter notebook downloads historical trades made on the Kraken Exchange from two sources.  The bulk of the trades (5.3m records) were downloaded from Kraken's Google Drive.  The most recent trades (1.3m records) were downloaded from the Kraken API.  

All of the data is synchronized and aggregated using Pandas time series aggregation functionality, and an analysis of the data was started.     

See the [blog post](https://nate23424533.wordpress.com/2022/12/05/building-a-crypto-trading-dashboard-the-first-steps/) or the related [Jupyter Notebook](notebook.ipynb) for further information.
