# Web Scraping: AI-Powered Data Extraction

Web scraping is a powerful technique used to extract and process data from websites. By leveraging AI-powered responses, this project offers a smarter and more efficient way to collect and analyze data from dynamic websites.

## What is Web Scraping with AI?

This web scraping tool combines the power of traditional scraping techniques with AI for enhanced data parsing and intelligent responses. Whether you're collecting product data, financial reports, or website content, this tool ensures you get the most relevant and insightful information.

The system uses **Selenium** for dynamic scraping, **BeautifulSoup** for parsing HTML, and **AI models** like **Ollama (LangChain)** for processing the scraped content, offering AI-powered insights similar to ChatGPT.

## Key Features

- **Dynamic Website Scraping**: Use Selenium to scrape content from websites that load data dynamically (e.g., tables, images).
- **AI-Powered Insights**: Leverage LangChain and Ollama models to generate insightful responses and analyses from the scraped data.
- **Content Cleaning**: Automatically clean and extract meaningful data, removing unwanted HTML tags, scripts, or styles.
- **User-Friendly Interface**: Streamlit integration allows for easy viewing and interaction with scraped data.

## How It Works

1. **Connect**: Start by connecting to the scraping browser (via Selenium WebDriver).
2. **Scrape**: Navigate to the target website and extract the HTML content.
3. **Process**: Clean the data using BeautifulSoup and apply AI models (Ollama) for insights.
4. **Display**: Use Streamlit for a simple and interactive UI to display the processed data.

## Built With 💻

- **Selenium**: Automates web browsers for scraping dynamic websites.
- **BeautifulSoup**: Used for parsing HTML and extracting relevant data.
- **Ollama (LangChain)**: Large language model for generating AI-powered responses from the scraped content.
- **Streamlit**: A framework for creating interactive web apps and displaying scraped data.
- **Bright Data**: Service used to automatically solve CAPTCHAs and prevent IP blocks during scraping.

## Why This Project?

Whether you're scraping product data, market analysis, or news articles, this project offers a fast, reliable, and AI-enhanced way to gather and process information. With intelligent parsing and content analysis, it goes beyond traditional web scraping to provide valuable insights from the data.

## Installation

To get started with this web scraping tool, follow these steps:

1)download chromedriver:- used to open any website by chrome browser --> https://googlechromelabs.github.io/chrome-for-testing/#stable
make sure the version of pc compateble with chromedrivare

2)download ollama:- needed to downloaded for using big data processing AI modules   ---> : https://ollama.com/

3)after downoading ollama specify the module and download
go to cmd and type  ```bash
ollama pull llama3.1

```bash
git clone https://github.com/your-username/web-scraping-ai.git
cd AI_web_info
pip install -r requirements.txt
streamlit run main.py
