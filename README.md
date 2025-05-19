# Web Scraping & Data Handling Challenge

## 📍 Website
**JustWatch India**  
🔗 [https://www.justwatch.com/in/movies?release_year_from=2000](https://www.justwatch.com/in/movies?release_year_from=2000)

---

## 📌 Objective

This project involves scraping **movie and TV show data** from JustWatch using **Python, BeautifulSoup, and Selenium**, performing **data filtering and analysis** with **Pandas**, and saving the final output to a CSV file.

---

## ✅ Tasks Overview

### 1. Web Scraping

Using `BeautifulSoup` and optionally `Selenium`, scrape the following data from individual **movie** and **TV show** pages (HTML only, no API usage):

#### a. Movie Information
- 🎬 Title
- 📅 Release Year
- 🏷️ Genre
- ⭐ IMDb Rating
- 📡 Available Streaming Services (e.g., Netflix, Prime, Hulu, etc.)
- 🔗 JustWatch URL

#### b. TV Show Information
- 📺 Title
- 📅 Release Year
- 🏷️ Genre
- ⭐ IMDb Rating
- 📡 Available Streaming Services
- 🔗 JustWatch URL

#### c. Scope
- Scrape data for **at least 50 movies** and **50 TV shows**
- Entry point can be popular content or genre filters to ensure diversity

---

### 2. Data Filtering & Analysis

Using `Pandas`, perform the following:

#### a. Filtering
- Include content released in the **last 2 years** (from today's date)
- Include only those with **IMDb rating ≥ 7**

#### b. Analysis
- 📊 Average IMDb rating for both movies and TV shows
- 🏷️ Top 5 genres with the most entries
- 🛰️ Streaming service with the **most available content**

---

### 3. Data Export

- Export the filtered and analyzed data to a CSV file  
- Store the CSV file in your **Google Drive Folder**
- Share a **view-only Drive link** in your Colab Notebook

---

## 📝 Submission Requirements

- Submit the **Colab Notebook link** with the `.py` script (code-only version)
- Include **clear comments** in your script explaining each major step:
  - Scraping logic
  - Filtering criteria
  - Analytical outputs
- Ensure the code is **error-free** and **runnable in one go**
- Add your **shared CSV Drive link** before the conclusion section in the notebook

---

## 📂 Deliverables

1. ✅ Colab Notebook with working code and explanation  
2. ✅ `justwatch_movies.csv` and `justwatch_tvshows.csv`  
3. ✅ Final filtered dataset as `justwatch_filtered.csv`  
4. ✅ Shared view link to Drive file in the Colab  
5. ✅ `README.md` (this file)

---

## 🔧 Tools & Libraries Used
- `requests` & `BeautifulSoup4` – HTML parsing
- `pandas` – Data handling & analysis
- `time`, `random` – To manage request pacing and user-agent rotation
---

## 📌 Notes
- Avoid API calls — use only client-side HTML scraping.
- Respect site crawling limits: use delays and rotate User-Agents to avoid blocking.
- Ensure modular, reusable code (e.g., separate functions for scraping movies, TV shows, services, etc.)

---

## 📬 Author
- [Anjali]
-

