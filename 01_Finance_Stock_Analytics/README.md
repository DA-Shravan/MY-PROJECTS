# 1 Automated Financial Data Scraper 📈

## 📌 Business Problem
Market analysts waste dozens of hours every week manually checking, copying, and archiving stock records and financial statement summaries across different web portals. This manual approach prevents the investment team from executing rapid, data-backed trading decisions. The objective of this project is to build an automated ingestion tool to programmatically extract and structure historical financial data.

## 🛠️ Data Architecture & Tech Stack
* **Core File:** `Python Web Scraping project_1.ipynb`
* **Tech Stack:** Python, BeautifulSoup, Requests, Pandas, JSON Parsing
* **Data Pipeline:** Targets structured HTML tables across financial web resources to harvest dynamic corporate financial tables, pricing milestones, and revenue records.

## 🔍 Key Insights & Data Engineering
* **HTML Dom Parsing:** Leveraged BeautifulSoup to isolate specific `<table>` elements and parse nested table rows (`<tr>`) and table data (`<td>`) while discarding irrelevant webpage scripts and ads.
* **Data Normalization:** Transformed messy, raw string scraped values (containing dollar signs, commas, and text markers) into clean numeric datatypes ready for time-series analysis.
* **Pipeline Resiliency:** Configured custom header requests to simulate browser interactions, avoiding automated server request blockages during data extraction.

## 🚀 Business Outcomes
* **Operational Efficiency:** Eliminated manual data entry completely by establishing a program that saves structured data frames straight to clean analytical formats.
* **Downstream Readies:** Created the foundation for historical stock performance models, allowing analysts to instantly feed clean historical inputs into visualization dashboards.


# 2 Stock Data Extraction and Visual Computing 📊

## 📌 Business Problem
Portfolio managers require a unified, side-by-side view comparing raw historical stock prices with corporate revenue trajectories to spot market anomalies. Relying on disconnected vendor screens makes it difficult to see when a company's stock price separates from its true financial fundamentals. This project solves that by merging live financial APIs with web-scraped data into a single visual window.

## 🛠️ Data Architecture & Tech Stack
* **Core File:** `Final Assignment-v2 (2).ipynb`
* **Tech Stack:** Python, yfinance API, BeautifulSoup, Pandas, Plotly / Matplotlib
* **Data Sources:** Extracts historical equity prices via the `yfinance` library and pairs it with web-scraped quarterly revenue data.

## 🔍 Key Insights & Engineering
* **API vs. Scraping Hybridization:** Successfully resolved mismatched data cadences by joining daily historical market pricing curves with quarterly corporate revenue figures into unified dataframes.
* **Data Integrity Checks:** Cleaned up inconsistencies where missing web-scraped revenue entries could have caused gaps in the structural data visualization.

## 🚀 Business Outcomes
* **Visual Intelligence:** Created a specialized graphing function that plots historical share prices right next to revenue bars on a unified timeline. 
* **Investment Clarity:** Empowered research teams to visually detect market valuation gaps—instantly highlighting periods where a company’s price spiked despite declining revenue numbers.