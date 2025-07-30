# 🕷️ Automated Web Scraper

A simple Python-based web scraping tool built in Google Colab.  
It extracts quotes from a website and stores them in a CSV file for analysis or automation.

---

## 🚀 Features

- Scrapes quotes from [quotes.toscrape.com](http://quotes.toscrape.com)
- Extracts and stores data in a structured format
- Option to run on a schedule (manual loop in Colab)
- Saves output as `.csv` file with timestamps

---

## 🧰 Technologies Used

- Python
- Google Colab
- `requests`
- `BeautifulSoup`
- `pandas`
- `datetime`

---

## 📁 How to Use

1. Open the `Web_Scraper.ipynb` notebook in Google Colab
2. Run all cells
3. The script will:
   - Fetch data from the quotes website
   - Parse quote texts
   - Save results to a CSV file
4. Optionally, run in a loop to scrape every X seconds

---

## 📌 Notes

- This project runs in **Google Colab**, not suitable for long-term scheduling.
- For full automation, consider deploying on:
  - A Raspberry Pi
  - A VPS with a cron job
  - A cloud platform like Heroku or Render

---

## 👤 Author

[shreeja A]  
[GitHub Profile](https://github.comcj25-shree)

---

