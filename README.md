# AI Startup Landscape Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Status:** In Progress


## Project Overview

This project is an end-to-end data pipeline designed to help venture capitalists identify emerging trends in the AI industry. It transforms unstructured web data into a clear, interactive Power BI dashboard that answers the question: **"Which sectors of the AI landscape are gaining the most momentum?"**

This project demonstrates skills in web scraping, data cleaning, natural language processing (NLP), SQL database management, and business intelligence storytelling.

---
## Tech Stack

* **Data Sourcing:** Python (Requests, BeautifulSoup)
* **Data Cleaning & Transformation:** Python (Pandas)
* **Data Storage:** SQLite
* **Data Analysis:** Python (NLP for categorization), SQL
* **Data Visualization:** Power BI

---
## Data Pipeline Workflow

1.  **Scrape:** Raw company data (name, description) is scraped from a live website (`builtin.com`) to simulate a real-world data acquisition scenario.
2.  **Clean & Structure:** The unstructured HTML is cleaned, processed, and organized into a structured format using Pandas.
3.  **Load & Query:** The clean data is loaded into a SQLite database for robust storage and initial querying.
4.  **Enrich (NLP):** A new `FocusArea` feature is engineered by applying a keyword-based NLP function to the company descriptions, adding a crucial layer of analytical value.
5.  **Visualize:** The final, enriched data is connected to Power BI to create an interactive dashboard that tells a clear and compelling story about emerging trends in the AI industry.

---
## Connect With Me
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/bfrancis360/). 
