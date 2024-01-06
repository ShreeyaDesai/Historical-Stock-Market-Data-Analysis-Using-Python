# Historical-Stock-Market-Data-Analysis-Using-Python
This Python script retrieves historical stock market data for a specified company and the NIFTY 50 index from the NSE India website. It performs basic operations on the data and generates a distribution plot comparing the high, low, open, and close indices.

**Dependencies:**
pandas: Data manipulation library
bs4 (Beautiful Soup): HTML parsing library
requests: HTTP library for making requests
datetime: Module for handling dates and times
StringIO: Provides a convenient way to work with text data as a file-like object
matplotlib: Plotting library
google.colab: Colab-specific library for file handling
seaborn: Data visualization library

**Functions:**

**getHistoryData:**
Retrieves historical stock market data for a specified company within a given date range.
Utilizes NSE India's API to fetch the data.

**niftyHistoryData:**
Retrieves historical data for a specified NIFTY index (e.g., NIFTY 50) within a given date range.
Scrapes data from the NSE India website using BeautifulSoup.

**Usage:
Data Retrieval:**
The script fetches historical data for Amazon shares ('AMZN') and the NIFTY 50 index within specified date ranges.

**Data Presentation:**
The retrieved dataframes are printed and saved as CSV files ('dataframe1.csv' and 'dataframe2.csv').
CSV files can be downloaded for further analysis.

**Basic Operations - Second Table:**
Basic statistical operations (sum, max, mean, median) and correlation are performed on the NIFTY 50 index data.

**Graph Generation - Distribution Plot:**
A distribution plot is created to visualize the distribution of high, low, open, and close indices for the NIFTY 50.
The graph is saved as 'graph5-1.png' and can be downloaded.
