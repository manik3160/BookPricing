# 📚 Book Pricing Web Scraping Project

This project is a beginner-friendly Python-based web scraper that collects book titles and their prices from [books.toscrape.com](https://books.toscrape.com), a dummy e-commerce site built for practicing scraping and data extraction.

## 🔍 Project Objective

The main goal is to automate the process of:
- Extracting book names and prices
- Saving the data in a structured format (CSV)
- Practicing web scraping using Python libraries

## 🛠️ Technologies Used

- Python 3
- Requests
- BeautifulSoup (bs4)
- Pandas
- OS (for directory management)

## 📁 Features

- Scrapes book data from all 50 pages of the site
- Extracts book title and price from each listing
- Saves all scraped data into a `data.csv` file
- Organizes raw HTML files in a folder named `htmls`

## 📌 Steps Followed

1. Imported required libraries
2. Created a folder to store raw HTML pages
3. Sent HTTP requests to each page using a loop
4. Parsed and extracted book titles and prices using BeautifulSoup
5. Stored the results in a Pandas DataFrame
6. Exported the final data to `data.csv`

## 📂 Output Sample

| Book Title                           | Price |
|--------------------------------------|-------|
| A Light in the Attic                | 51.77 |
| Tipping the Velvet                  | 53.74 |
| Soumission                          | 50.10 |
| ...                                  | ...   |

## ✅ Learning Outcomes

- Understood the basics of web scraping and HTML parsing
- Practiced working with loops, conditionals, and data cleaning
- Gained experience in real-world data handling using Pandas
- Built a reusable structure for future scraping projects

## 📎 Note

This project is for learning purposes only and scrapes data from a public practice website.



