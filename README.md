# 🌍 Wikipedia GDP Scraper
# 📌 Project Overview

This project is a Python-based web scraping tool that extracts GDP data by country/territory from Wikipedia. Using BeautifulSoup and Pandas, the scraped data is cleaned, structured into a DataFrame, and exported as a CSV file for further analysis and visualization.

# 🚀 Features

🔎 Scrapes global GDP data from Wikipedia tables

🧹 Cleans and structures raw HTML data into a usable DataFrame

📊 Exports data to CSV format for analysis

⚡ Easy to run in VS Code or Jupyter Notebook

🔗 Works with real-time data updates from Wikipedia

🛠️ Tech Stack

🐍 Python 3.x

📦 Pandas

🌐 BeautifulSoup4

⚙️ Requests

# 🔧 Installation & Setup

# 1️⃣ Clone the repository

git clone https://github.com/your-username/WikiGDP-Scraper.git
cd WikiGDP-Scraper


# 2️⃣ Create and activate a virtual environment

python -m venv venv
venv\Scripts\activate   # For Windows
source venv/bin/activate   # For Mac/Linux


# 3️⃣ Install dependencies

pip install -r requirements.txt

# ▶️ Usage

Run the scraper to fetch GDP data:

python src/scraper.py


# 💾 Output will be saved as:

data/gdp_by_country.csv

# 📊 Sample Output
Country/Territory	IMF (2025)	World Bank (2022–24)	United Nations (2023)
World	113795678	111326370	100834796
United States	30507217	29184890	27720700
China	19231705	18743803	17794782
Germany	4744804	4659929	4525704
India	4187017	3912686	3575778
# 🧑‍💻 Author

👤 HASHIM
💼 Project for CodeAlpha Internship

# ⭐ Acknowledgements

📖 Wikipedia for providing open data

🐼 Pandas & 🥣 BeautifulSoup for making data handling easy
