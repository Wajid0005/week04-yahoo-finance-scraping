# Yahoo Finance Web Scraping 📈

A clean Python project that scrapes **stock-specific financial news** from Yahoo Finance for the ticker **RELIANCE.NS**, using `requests` and `BeautifulSoup`, and saves it to a CSV.

---

## 🚀 What This Does

- Fetches the Yahoo Finance news page for a given stock
- Parses HTML to extract:
  - Headline
  - Article URL
  - Publisher (e.g., Reuters)
  - Published time (e.g., “2h ago”)
  - Scrape timestamp
- Stores results in a structured CSV

---

## 🧠 Tools Used

- Python
- `requests`
- `BeautifulSoup`
- `pandas`

---

## 📍 Data Source

**Yahoo Finance — Reliance Industries news**  
`https://finance.yahoo.com/quote/RELIANCE.NS/news`

---

## 📦 Output

**File:** `reliance_yahoo_finance_news.csv`

**Columns:**

| Column           | Meaning |
|------------------|---------|
| `stock`          | Stock ticker (RELIANCE.NS) |
| `headline`       | News headline |
| `article_url`    | Link to article |
| `source`         | Publisher |
| `published_time` | Time relative (e.g., “3h ago”) |
| `scraped_at`     | UTC scrape timestamp |

---

## 📌 How to Run

1. Clone this repo
2. Install requirements:
   ```bash
   pip install requests beautifulsoup4 pandas
