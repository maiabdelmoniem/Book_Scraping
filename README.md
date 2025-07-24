readme_text = """
# 📚 BookScraper

**BookScraper** is a simple Python script that scrapes book data (title, price, and stock availability) from [Books to Scrape](http://books.toscrape.com), a website built specifically for practicing web scraping.

This project is ideal for beginners learning **BeautifulSoup**, **requests**, and **data export** using **pandas**.

---

## 🔍 What It Does

The script:

- Loops through all pages of the site  
- Extracts each book's **title**, **price**, and **stock status**  
- Saves the collected data into three formats:  
  - `books.json`
  - `books.csv`
  - `books.xlsx`

---

## 🛠️ Requirements

Install the required Python packages:

```bash
pip install requests beautifulsoup4 pandas
