# Amazon Price Tracker – Web Scraping & Automation

**Live price monitoring** of OnePlus 9 Pro on Amazon.de using **Python, BeautifulSoup, and automated daily checks**.

---

## Overview

This project **scrapes product title and price** from Amazon.de, **saves data to CSV**, and runs **automatically every 24 hours** to track price changes over time.

- **Goal**: Build a lightweight, automated price tracker.
- **Tech Stack**: Python, `requests`, `BeautifulSoup`, `pandas`, `csv`, `time`, `smtplib` (optional email alert)
- **Output**: `AmazonWebScraperDataset.csv` with columns: `Title`, `Price`, `Date`

---

## Features

- Extracts **product title** and **current price** from Amazon product page  
- Cleans and formats data (removes extra whitespace, currency symbols)  
- Appends **timestamp** to every entry  
- Runs **automatically every 24 hours** using `while(True)` + `time.sleep(86400)`  
- (Optional) Sends **email alert** when price drops below threshold  

---



### Notes

Amazon may block frequent requests — use responsibly.
Headers include realistic User-Agent to mimic browser.
Price parsing uses [1:6] — adjust if format changes.
Use cron or Task Scheduler for production deployment.
