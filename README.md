---

# 🎬 Top 100 Movies Web Scraper

A beginner-friendly Python script that scrapes the **Top 100 Movies of All Time** from an archived version of Empire Online using `BeautifulSoup`. The final list is saved to a `.txt` file in the correct ranking order (from 1 to 100).

---

## 🚀 Features

* **Web Scraping with BeautifulSoup** — Extracts movie titles from structured HTML content.
* **Reverse Ordering** — The original list is from #100 to #1; this script reorders it from #1 to #100.
* **Clean Output** — Saves the final list to a UTF-8 encoded `movies.txt` file.
* **Efficient Parsing** — Uses HTML tag and class targeting to fetch only what’s needed.

---

## ⚙️ How It Works

1. Sends a GET request to the archived webpage using `requests`.
2. Parses the HTML using `BeautifulSoup`.
3. Finds all `<h3 class="title">` elements.
4. Extracts text from each tag and strips whitespace.
5. Reverses the list and writes it to `movies.txt`.

---

## 🧰 Technologies Used

* **Python**
* **requests** — for fetching web content
* **BeautifulSoup (bs4)** — for parsing HTML
* **UTF-8 text file output** — for cross-platform compatibility

---

## 🛠️ Setup Guide

### 1. Clone the Repository

```bash
git clone https://github.com/AbdulRehmanMarfani/top-100-movies-scraper.git
cd top-100-movies-scraper
```

### 2. Install Dependencies

```bash
pip install requests beautifulsoup4
```

### 3. Run the Script

```bash
python main.py
```

> The `movies.txt` file will be generated in the same directory.

---

## 📬 Example Output

```
1. The Godfather
2. The Empire Strikes Back
3. The Dark Knight
...
100. Avengers: Endgame
```

---

## 🔐 Notes

* Always respect a website’s `robots.txt` before scraping.
* This project uses a snapshot from the **Wayback Machine** to avoid issues with dynamic websites.

---

## 🌐 Source

* [Original Article (Archived)](https://web.archive.org/web/20200518073855/https://www.empireonline.com/movies/features/best-movies-2/)

---

## 👨‍💻 Author

**Abdul Rehman Marfani**
[🌐 Portfolio](https://abdulrehmanmarfani.github.io/portfolio) • [🐙 GitHub](https://github.com/AbdulRehmanMarfani) • [💼 LinkedIn](https://www.linkedin.com/in/abdul-rehman-marfani-4aa587276)

