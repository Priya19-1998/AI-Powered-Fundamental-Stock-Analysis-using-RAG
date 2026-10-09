# AI-Powered Fundamental Stock Analysis using RAG

## 1. Objective

The objective of this project is to analyze Apple's financial information using a Retrieval-Augmented Generation (RAG) system. The project collects financial data, creates text embeddings, stores them in a FAISS index, and retrieves relevant information to answer financial questions.

## 2. Company Selected

* **Company Name:** Apple Inc.
* **Stock Symbol:** AAPL
* **Data Source:** Yahoo Finance

## 3. Tools and Technologies Used

* Python
* Google Colab
* Yahoo Finance (`yfinance`)
* Pandas and NumPy
* Sentence Transformers
* FAISS
* Google Gemini

## 4. What We Did

1. Collected Apple's company details and financial information from Yahoo Finance.
2. Retrieved the income statement, balance sheet, cash flow statement, historical stock prices, and financial metrics.
3. Converted the financial information into text.
4. Split the text into smaller chunks for processing.
5. Generated embeddings using the `all-MiniLM-L6-v2` model.
6. Created a FAISS index to store and search the embeddings.
7. Tested the retrieval system using financial questions.
8. Connected Google Gemini to generate answers using the retrieved financial information.

## 5. Results and Financial Analysis

The collected data provided the following results:

* **Revenue:** Approximately $466.82 billion.
* **Net Income:** Approximately $128.93 billion in the financial metrics retrieved.
* **Earnings Per Share (EPS):** 8.72.
* **Profit Margin:** Approximately 27.62%.
* **Operating Margin:** Approximately 32.62%.
* **Free Cash Flow:** Approximately $107.72 billion in the financial metrics retrieved.
* **Historical Stock Price Increase:** Approximately 144.39% between the first and latest closing prices in the downloaded five-year dataset.

The balance sheet and cash flow statement also provided information about Apple's assets, liabilities, debt, cash position, and operating cash flow.

These results suggest that Apple has high revenue and profitability. However, debt and changes in financial performance should also be considered.


## 6. Conclusion

In this project, we collected Apple's financial data and built a basic RAG system using Python, Sentence Transformers, and FAISS. The system retrieved relevant financial information for questions about revenue, net income, EPS, and historical stock performance.

Google Gemini was integrated to generate answers from the retrieved information. However, API quota limitations prevented us from completing every planned question test.

This project helped demonstrate how financial data and RAG can be combined to support fundamental stock analysis.
