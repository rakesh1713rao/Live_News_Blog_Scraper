# Live_News_Blog_Scraper

A Python-based Web Scraping Practice Project

# 📌 Overview

This project is a structured **web scraping practice implementation** built using Python. It extracts live news updates from a publicly available liveblog page and organizes the information into a structured dataset.
The objective of this project was to strengthen understanding of:
- HTTP requests and headers
- HTML parsing and DOM navigation
- Handling dynamic web structures
- Writing modular scraping functions
- Structuring data using Pandas
- Debugging real-world scraping challenges

⚠️ This project was developed strictly for educational and skill-building purposes. It is not affiliated with or endorsed by any news organization.

# 🛠 Tech Stack

- **Python 3**
- **requests** – HTTP requests handling
- **BeautifulSoup (bs4)** – HTML parsing
- **pandas** – Data structuring and analysis
- **Jupyter Notebook** – Development environment

# 📂 Project Structure
```

live-news-scraper/
│
├── scraper.ipynb        # Main scraping notebook
├── requirements.txt     # Project dependencies
└── README.md            # Project documentation

```
# 🚀 Features

- Custom HTTP headers to mimic real browser requests
- Modular scraping functions:
```
get_time_updates()
get_title_updates()
get_description_updates()
```
- Structured extraction into dictionary format
- Conversion into Pandas DataFrame
- Clean and readable data output

# 🔎 Workflow

- **1.** Send HTTP GET request with custom headers
- **2.** Parse page content using BeautifulSoup
- **3.** Identify structured content blocks
- **4.** Extract:
  - 🕒 Timestamp
  - 📰 Headline
  - 📄 Description
- **5.** Store results in a structured DataFrame

# 🧠 Key Learning Outcomes

- Understanding how HTTP headers affect server responses
- Handling dynamic and nested HTML structures
- Debugging common scraping issues
- Designing modular scraping functions
- Structuring web data for analysis

# ⚖️ Disclaimer

This project was created strictly for **educational and skill-development purposes**.

All content belongs to its respective publisher.
No scraped data is stored, redistributed, or used commercially.

