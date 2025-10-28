# 🛒 Amazon Web Scraper

A simple Python project that extracts product information (title, price, and availability) from Amazon product pages and exports the data into a clean, structured CSV or Excel file for analysis.

## 🧰 Tech Stack
- **Python**
- **BeautifulSoup** (HTML parsing)
- **Requests** (HTTP requests)
- **Pandas / CSV** (data storage)
- **lxml** (HTML parser)

## ⚙️ Features
- Scrapes multiple Amazon product pages listed in `url.txt`
- Extracts product title, price, and availability
- Saves data with the current date into `AmazonWebScraperDataset.csv`
- Simple and lightweight—no API keys required

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-web-scraper.git
   cd amazon-web-scraper

## Install dependencies
pip install requests beautifulsoup4 lxml pandas

python main.py

| Title                                 | Price  | Date       |
| ------------------------------------- | ------ | ---------- |
| Data Systems Business Analyst T-Shirt | $19.99 | 2025-10-28 |
