# Task 04: E-Commerce Web Scraper

## 📌 Project Description
This project is an automated **Web Scraper** developed as part of the SkillCraft Technology internship. The program is designed to browse an e-commerce website, extract key product details—such as **Names, Prices, and Ratings**—and store them in a structured **CSV (Comma Separated Values)** format.



[Image of web scraping workflow diagram]


Manual data collection is time-consuming and prone to errors. This tool demonstrates how to use Python to transform unstructured web data into a clean dataset ready for analysis.

---

## 🚀 Features
* **Automated Extraction:** Scrapes multiple products simultaneously.
* **Data Parsing:** Uses BeautifulSoup to navigate complex HTML structures.
* **Structured Storage:** Automatically formats and saves data into a `products.csv` file.
* **Custom Headers:** Includes a User-Agent to mimic a real browser and improve request success rates.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Requests:** To send HTTP requests and retrieve webpage content.
* **BeautifulSoup4:** To parse HTML and extract specific data points.
* **CSV Module:** To handle data writing and file creation.

---

## 📂 Project Structure
1. **Request:** The script connects to the target URL.
2. **Parsing:** The HTML is scanned for specific tags (e.g., `<h3>` for titles, `<p>` for prices).
3. **Data Cleaning:** Raw text is stripped of unnecessary characters and whitespace.
4. **Export:** The final list is written into a CSV file with clear headers.

---

## ⚙️ How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/ecommerce-scraper.git](https://github.com/your-username/ecommerce-scraper.git)
   cd ecommerce-scraper
