# 📚 Book Scraper – Web Scraping Book Data

A Python-based web scraping project that extracts book details such as **title, price, rating, availability**, and more directly from the home page of an online bookstore. The project uses `Requests` and `BeautifulSoup` to fetch and parse data, making it ideal for beginners learning web scraping.

---

## 📌 Project Overview

This project scrapes book-related information from a books website and stores the cleaned data for further analysis.

### ✔️ What It Does

* Scrapes book titles
* Scrapes pricing information
* Extracts product ratings
* Captures stock availability
* Saves all data into a structured format (CSV/DataFrame)
* Displays extracted results inside the Jupyter Notebook

---

## 🛠️ Tech Stack

### **Languages & Tools**

* Python
* Jupyter Notebook

### **Libraries Used**

* `requests` – Fetching webpage HTML
* `BeautifulSoup` – HTML parsing
* `pandas` – Storing and cleaning scraped data
* `lxml` or `html.parser` (optional)

---

## 📂 Project Structure

```
📦 Book-Scraper
├── 📄 Book Scraper - Scraping Book data from Home Page.ipynb
├── 📄 README.md
├── 📁 data
│   └── books.csv (exported data)
└── 📁 images (optional)
```

---

## ▶️ How to Run the Project

### **1. Clone the Repository**

```bash
git clone https://github.com/your-username/book-scraper.git
cd book-scraper
```

### **2. Install Required Libraries**

```bash
pip install requests beautifulsoup4 pandas
```

### **3. Run the Notebook**

```bash
jupyter notebook
```

Open the file: **Book Scraper - Scraping Book data from Home Page.ipynb**

---

## 📊 Output Format

The scraper extracts:

* **Book Title**
* **Book Price**
* **Book Rating** (One to Five Stars)
* **Availability Status**

You can export results to:

* CSV
* Excel
* Pandas DataFrame

Example (CSV preview):

```
Title,Price,Rating,Availability
"A Light in the Attic",£51.77,3,"In stock"
"Tipping the Velvet",£53.74,1,"In stock"
"Soumission",£50.10,1,"In stock"
```

---

## 🖼️ Screenshots (Optional)

Add screenshots like:

```<img width="1331" height="584" alt="image" src="https://github.com/user-attachments/assets/44fe7eee-8dae-4840-be9f-74759905214b" />

```<img width="980" height="294" alt="image" src="https://github.com/user-attachments/assets/0e0442e2-97ce-4dfa-8146-33731ce897c0" />


```

---

## 🧩 Features You Can Add

* Pagination scraping
* Category-wise scraping
* Image scraping
* Database export
* API integration

---

## 🤝 Contributing

Contributions are welcome!
If you have ideas to improve scraping logic or add features, feel free to submit a pull request.

---

## 📜 License

This project is licensed under the **Apache**.

---

## ⭐ Support

If you find this project useful, don’t forget to **star ⭐ the repository** on GitHub!
