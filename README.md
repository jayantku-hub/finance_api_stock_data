---

# Finance API – Stock Price Data Extraction (Python)

This project demonstrates how to extract **real-time stock price data** using a Finance API, process the JSON response, and store the data in a structured format for analysis.

The project is designed for **beginners learning APIs, Python, and data analysis**, and can be run in **Google Colab** or any Python environment.

---

## Project Objective

* Fetch live stock market data using a Finance API
* Extract important stock details from JSON response
* Store data in tabular format using Pandas
* Prepare data for analysis, dashboards, and reports

---

## Concepts Covered

* Finance APIs
* HTTP GET requests
* API authentication using API keys
* JSON parsing
* Looping through multiple stock symbols
* Data extraction and transformation
* CSV-ready data structure

---

## Tech Stack

* Python
* requests
* pandas
* Alpha Vantage API

---

## API Information

* Provider: Alpha Vantage
* Endpoint:

```
https://www.alphavantage.co/query
```

A free API key is required to run this project.

---

## Project Workflow

1. Define a list of stock symbols
2. Send API requests for each stock
3. Receive market data in JSON format
4. Extract relevant stock information
5. Store data in a structured table

---

## Data Extracted

* Stock Symbol
* Current Price
* Previous Close Price
* Percentage Change

---

## Output

* Structured stock price data ready for analysis
* Can be exported to CSV or used for dashboards

---

## Use Cases

* Stock analysis
* Trading dashboards
* Financial reports
* FinTech and market research projects

---

## Notes

* API rate limits apply for free accounts
* API keys should not be shared publicly
* Delay is added between requests to avoid API blocking

---

## Conclusion

This project provides a practical introduction to Finance APIs and demonstrates how real-world financial data is collected and prepared for analysis using Python.

