# Amman Stock Exchange (ASE) Scraping Project

This Jupyter Notebook scrapes detailed trading data from the Amman Stock Exchange (ASE) website, specifically covering:

## 📈 From Daily Summary:
- **Regular Market**:
  - Trading Value, Trading Volume, Number of Transactions, Number of Securities
  - Top Gainers, Top Losers, Unchanged Companies
- **OTC Market**:
  - Trading Value, Trading Volume, Number of Transactions, Number of Securities
  - Top Gainers, Top Losers, Unchanged Companies
- **Bonds Market**:
  - Trading Value, Trading Volume, Number of Transactions, Number of Securities
  - Top Gainers, Top Losers, Unchanged Companies
- **Sukuk Market**:
  - Trading Value, Trading Volume, Number of Transactions, Number of Securities
  - Top Gainers, Top Losers, Unchanged Companies

Each section is extracted and stored into a **separate DataFrame** for further processing.

## 📈 From The Market Today:
- **Live Market Data** including:
  - Index
  - Value
  - Change
  - Percent
  - Market Status
  - Month
  - Day
  - Time
  - Date

This live data is also stored into a dedicated **DataFrame**.

---

## 🛠️ Technologies Used
- Python
- Requests
- BeautifulSoup (bs4)
- Network Request Analysis (using browser DevTools)
- Direct JSON/API extraction
- Pandas

## 🗂️ Output Formats
- Separate and clean DataFrames
- Ready to download as Excel (`.xlsx`) files
- Ready for insertion into SQL Server databases
