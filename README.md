# Web Scraping Project 🕷️📊

This project demonstrates **Python-based web scraping** using `requests`, `BeautifulSoup`, and `pandas`.  
It covers multiple scraping use cases: job listings, product listings, and tabular data.

  
## 📌 Features

### 1. RemoteOK Job Scraper
- Scrapes remote **Python developer jobs** from [RemoteOK](https://remoteok.com/remote-dev+python-jobs).
- Extracts:
  - **Job Title**
  - **Company**
  - **Job Link**
- Saves results into a list of dictionaries.

### 2. Books to Scrape (Science Category)
- Scrapes science books from [Books to Scrape](https://books.toscrape.com).
- Extracts:
  - **Title**
  - **Price**
  - **Rating (1–5 stars)**
- Cleans the price string using regex and converts ratings into numbers.
- Loads data into a `pandas DataFrame`.

### 3. Population by Country (Worldometers)
- Demonstrates scraping tabular data from [Worldometers](https://www.worldometers.info/world-population/population-by-country/).
- Can be extended to store results in SQLite or CSV.

---

## 🛠️ Tech Stack
- **Python 3**
- **Libraries:**
  - `requests` → Fetch HTML
  - `BeautifulSoup (bs4)` → Parse HTML
  - `pandas` → Store & manipulate data
  - `re` → Regex cleaning
  - `sqlite3` (optional) → Store results in a local database

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AshXplorer0420/webscrapping.git
   cd webscrapping
