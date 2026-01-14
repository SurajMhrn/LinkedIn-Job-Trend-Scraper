# LinkedIn Job Trend Analysis (Web Scraping) 📊

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![BeautifulSoup](https://img.shields.io/badge/Library-BeautifulSoup-green)

## 📖 Overview
This project is a web scraping and data analysis tool designed to extract job postings from LinkedIn. The goal is to analyze current market trends, specifically focusing on the demand for specific skills across different cities and job roles. By processing this data, we generate insights that help job seekers and recruiters understand the "Skill vs. Role" matrix and geographical demand.

## 🎯 Objectives
* **Scrape Data:** Automate the extraction of job titles, locations, companies, and required skills from LinkedIn job posts.
* **Analyze Trends:** Identify top in-demand skills for specific roles (e.g., Data Scientist, Web Developer).
* **Visualise Insights:** Create heatmaps and matrices to represent skill density by city.
* **Recommend:** Provide data-driven recommendations for job seekers based on high-demand skills.

## 🛠️ Tools & Technologies
* **Python:** Core programming language.
* **BeautifulSoup (bs4):** For parsing HTML and scraping job details.
* **Pandas:** For data cleaning, manipulation, and creating the Skill vs. Role matrix.
* **Matplotlib/Seaborn:** For generating trend analysis visuals and heatmaps.
* **Excel:** Used for final data storage and reporting.

## 📂 Project Structure
```text
├── data/                   # Raw and processed datasets
├── project 14.ipynb        # Main Jupyter Notebook with scraping & analysis logic
├── README.md               # Project documentation
└── requirements.txt        # List of dependencies
