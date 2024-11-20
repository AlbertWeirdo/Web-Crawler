# Stock Price Extraction Project

## Overview

This project is designed to automate the extraction of stock price data from [反散戶小台多空比 - 期權 | 玩股網](https://www.wantgoo.com/futures/retail-anti-indicator) using Java and Selenium. The primary goal is to collect and organize stock price information, such as closing prices, long positions, short positions, and net long/short ratios, into an Excel file for further analysis. By leveraging Selenium, this project is capable of handling dynamically loaded content on web pages, ensuring that all relevant data is extracted accurately.

---

## How It Works

1. **Webpage Interaction**:
   - Selenium WebDriver is used to programmatically access the webpage.
   - It simulates user interactions such as opening the page and waiting for dynamic content to load.

2. **Dynamic Content Handling**:
   - The webpage data is rendered dynamically using JavaScript. Selenium ensures that the content is fully loaded before proceeding with the extraction process.

3. **Data Extraction**:
   - Selenium locates the HTML elements containing stock price information, such as tables or specific data fields.
   - The data is extracted row by row, capturing key metrics like dates, closing prices, and net ratios.

4. **Data Storage**:
   - The extracted data is organized and saved into an Excel file 

5. **Automation Benefits**:
   - This project automates repetitive data collection tasks, reducing manual effort and improving data accuracy.

---

## Key Features

- **Handles Dynamic Content**:
  - Selenium's ability to wait for JavaScript-rendered content ensures reliable data extraction even for complex web pages.

- **Structured Data Output**:
  - The project organizes extracted information into an Excel file, making it easy to review and analyze.

This project is ideal for users looking to automate data collection from dynamic webpages for financial or analytical purposes.
