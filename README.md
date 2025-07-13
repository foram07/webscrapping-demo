# 📚 Books to Scrape – Web Scraping Demo

A simple yet effective web scraping script built with Python to extract book data (title, price, availability, and rating) from [BooksToScrape.com](http://books.toscrape.com), a website designed specifically for practicing web scraping.

---

## 🚀 What This Script Does

- Navigates through all paginated pages on the site
- Extracts book details such as:
  - 📖 Title
  - 💵 Price
  - 📦 Availability
  - ⭐ Rating (converted to numeric scale)
- Stores the data in a structured pandas DataFrame
- Optionally saves the result as a CSV (you can easily add it)

---

## 🛠 Tech Stack

- `requests` – for sending HTTP requests  
- `BeautifulSoup` – for HTML parsing and element extraction  
- `pandas` – for data structuring and analysis  
- `time` – for adding polite delays between requests

---

## 💡 Why This Project?

- Learn real-world web scraping techniques  
- Practice looping through paginated sites  
- Gain experience in HTML parsing and data cleaning  
- Can be extended to save into CSV, database, or used for analysis

---

## 📦 How to Run

1. Clone this repo or copy the script into your local environment.

2. Make sure you have the dependencies installed:

```bash
pip install requests beautifulsoup4 pandas
