# Extracting-and-visualizing-stock-data

Project Overview

This project focuses on extracting and visualizing stock data for two major companies, Tesla and GameStop, using Python libraries like yfinance, pandas, and plotly. The analysis also incorporates web scraping techniques to obtain historical revenue data from online sources. The goal is to create interactive visualizations that depict the historical share prices and revenue trends for these companies, providing insights into their financial performance over time.

Project Structure

Data Extraction

Stock Data Extraction: The yfinance library is utilized to download historical stock data for Tesla (TSLA) and GameStop (GME). The data includes key metrics such as the opening and closing prices, volume, and dates.

Revenue Data Extraction: Web scraping techniques are employed to gather quarterly revenue data from MacroTrends. The BeautifulSoup library is used to parse HTML content and extract relevant tables, which are then cleaned and prepared for analysis.
Data Visualization

Graphing Function: A custom function make_graph is defined to create a dual-subplot visualization using the plotly library. The first subplot displays the historical share price, and the second one shows the historical revenue data. This function allows for an easy comparison of stock performance against company revenue over time.

Tesla Visualization: The extracted data for Tesla is visualized using the make_graph function, providing a clear picture of the company's stock price and revenue trends.

GameStop Visualization: Similarly, the GameStop data is plotted to illustrate the correlation between its stock performance and revenue.


Tools and Technologies

Python: The core programming language used for data manipulation and visualization.

yfinance: A Python library for accessing stock market data.

pandas: Used for data manipulation and cleaning.

BeautifulSoup: A library for web scraping, specifically to extract revenue data from HTML tables.

plotly: A graphing library used to create interactive visualizations.



Results

The project provides visual insights into the historical performance of Tesla and GameStop by plotting their stock prices alongside revenue data. These visualizations allow for an intuitive understanding of how stock prices correlate with the companies' financial health over time.
