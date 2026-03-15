# 💰 Cryptocurrency Market Tracker (BeautifulSoup and Python)

## 📌 Project Overview

This project demonstrates how to scrape cryptocurrency market data from the website **CoinMarketCap** using Python.
The script collects information such as **coin name, price, market capitalization, and 24-hour price change**, then stores the data in a structured CSV dataset for further data analysis.

This project is a simple example of **web scraping for data science**, using the libraries `requests`, `BeautifulSoup`, and `pandas`.

---

## Table of Contents

- [Data Source](data-source)
- [Data Collected](data-collected)
- [Technologies Used](technologies-used)
- [Project Structure](project-sture)
- [Project Workflow](project-workflow)
- [Output](output)
- [Author](author)

---

## 🌐 Data Source

Data is scraped from:
https://coinmarketcap.com

The scraper navigates through multiple pages of the cryptocurrency ranking table.

---

## 📊 Data Collected

The script extracts the following fields for each cryptocurrency:

| Column Name | Description                                  |
| ----------- | -------------------------------------------- |
| Coin Name   | Name of the cryptocurrency                   |
| Price       | Current price of the cryptocurrency          |
| Market Cap  | Total market capitalization                  |
| 24h Change  | Percentage price change in the last 24 hours |

---

## 🛠 Technologies Used

* Python
* requests
* BeautifulSoup (bs4)
* pandas

---

## 🗃️ Project Structure

Cryptocurrency_market_tracker

|- crypto_scraping.py

├ crypto_market_tracker.csv

└ README.md

---

## 📂 Project Workflow

1. Send an HTTP request to the CoinMarketCap webpage.
2. Parse the HTML content using BeautifulSoup.
3. Extract cryptocurrency information from the table.
4. Store the extracted data in a list of dictionaries.
5. Convert the data into a pandas DataFrame.
6. Export the dataset to a CSV file.

---

## 📁 Output

Example output structure:

| Coin Name | Price  | Market Cap | 24h Change |
| --------- | ------ | ---------- | ---------- |
| Bitcoin   | $69000 | $1.35T     | +0.45%     |
| Ethereum  | $2100  | $250B      | +0.30%     |
| Tether    | $1.00  | $100B      | +0.01%     |


---

## 👨‍💻 Author

`Developed as a **Data Science Web Scraping Mini Project using Python**.`

Author: Ranjan Singh

Project Type: Web Scraping / Data Collection

Language: Python
