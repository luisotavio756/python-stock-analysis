<h1  align="center">Python B3 stock analysis</h1>
<div align="center">
	<img src="/assets/banner.png" />
</div>
<p align="center">
    <a href="#rocket-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#information_source-how-to-use">How To Use</a>&nbsp;&nbsp;&nbsp;
</p>

## :rocket: Technologies

It's interesting how in 2 seconds, with Python, we can capture the more than 400 stocks listed on the Brazilian stock exchange (IBOV), apply filters and generate reports that can help with stock analysis.

This is what Thiago Lolkus Nigro did in one of his recent videos, which I thought was very cool. It was all done using an Excel spreadsheet.
https://www.youtube.com/watch?v=UccLCH0OK7M

So I thought I'd do the same thing, only in an automated way. To do this, I used a Web Scrapping strategy to extract the shares and their main indicators from a website, I used the Pandas data processing tool and a tool to generate PDF reports.

Dividend Yield between 6% and 12%, ROE over 13%, P/L between 3 and 10 and growth over 10% were some of the filters. Through these and other filters, it was possible to process a mass of data of around 400 records and get a result with only the desired stocks. And with this automation, we could do it in seconds.

- [Pandas](https://pandas.pydata.org/)
- [BeautifulSoup4](https://pypi.org/project/beautifulsoup4/)

## :information_source: How To Use

For use, you need clone and run this steps from your command line:

```bash

# Clone this repository

$ git clone https://github.com/luisotavio756/python-stock-analysis.git

# Go into the repository

$ cd python-stock-analysis

# Install dependencies

$ pip install pandas requests bs4 reportlab

# Run

$ python3 main.ipynb

```

---

Made by Luis Otávio
