# Quotes_Analysis

A project to scrape quotes from the web, perform Exploratory Data Analysis (EDA) with Python, and visualize the insights using Power BI.

## 📝 Project Overview

This project collects quotes, along with their authors and tags, from the public website `quotes.toscrape.com`. After scraping and cleaning the data, it performs EDA to discover patterns such as the most quoted authors, most common themes (tags), and the distribution of quote-lengths. Finally, it presents these findings in an interactive Power BI dashboard for easy exploration.

## 📂 Repository Structure

```
├── Web_scraping_with_EDA.ipynb   — Python notebook for scraping + EDA  
├── quotes.csv                    — Scraped dataset (CSV)  
├── Quotes_Analysis.pbix          — Power BI dashboard file  
├── README.md                     — (this file) project overview and instructions  
```

## ⚙️ How to Use / Run the Project

1. **Run the Python Notebook**  
   - Open `Web_scraping_with_EDA.ipynb`  
   - Run all cells to scrape quotes, clean data, and generate analysis plots and the CSV file `quotes.csv`.  

2. **Load data into Power BI**  
   - Open `Quotes_Analysis.pbix` in Power BI Desktop — it already connects to `quotes.csv` and contains prepared visuals.  
   - *Or*, if you prefer to build the dashboard yourself:  
     - Load `quotes.csv` in Power BI → transform data (split tags, create quote-length column) → add visuals: top authors, most common tags, quote-length distribution, and KPI cards.

## 📊 What You Get / Key Insights

- **Top 10 Most Quoted Authors** — who appears most frequently.  
- **Top 10 Most Common Tags** — the most frequent themes across quotes (e.g. “life”, “inspirational”, “love”).  
- **Quote Length Distribution** — insights into how long typical quotes are.  
- **Easy Filtering** — you can filter by author or tag to explore subsets.  

## ✅ Conclusion

This project shows end-to-end data workflow: web scraping → data cleaning → analysis → visualization.  
It demonstrates how raw web data can be transformed into meaningful insights using Python and Power BI.  
It’s a strong portfolio piece for data science, data analysis, or data engineering skills.

## 📚 Dependencies & Requirements

- Python libraries: `requests`, `beautifulsoup4`, `pandas`, `matplotlib`, `seaborn`, `wordcloud`  
- Power BI Desktop (any recent version)  

## 🧑‍💻 About / Author

Created by **Abinaya Kathirvel**.  
If you find any bug or want to contribute — you are welcome to fork and raise a pull request.  

