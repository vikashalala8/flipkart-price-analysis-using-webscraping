# Flipkart Product Price Analysis Using Web Scraping

## 📌 Project Description

This project performs **price analysis of laptops and washing machines available on Flipkart** using **web scraping and exploratory data analysis (EDA)**. Product data is extracted from Flipkart, cleaned, and analyzed to understand **price distribution, ratings, reviews, specifications, and correlations** between different features.

The analysis helps identify **pricing patterns, popular product ranges, and relationships between price and product attributes**.

---

## 🎯 Objectives

* Scrape product data from Flipkart
* Analyze laptop and washing machine prices
* Perform data cleaning and preprocessing
* Conduct univariate, bivariate, and multivariate analysis
* Visualize insights using charts and plots

---

## 🛠 Libraries & Tools Used

```python
import requests
import pandas as pd
import numpy as np
from bs4 import BeautifulSoup
import re
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
```

---

## 📊 Project Workflow

1. **Data Extraction**

   * Scraped product data from Flipkart using `requests` and `BeautifulSoup`
2. **DataFrame Creation**

   * Converted extracted data into Pandas DataFrames
3. **Data Storage**

   * Exported data into CSV format
4. **Data Cleaning**

   * Handled missing values, cleaned prices, ratings, and text data
5. **Exploratory Data Analysis (EDA)**

   * Univariate, bivariate, and multivariate analysis
6. **Visualization**

   * Used Matplotlib and Seaborn for insights

---

## 🖥 Products Analyzed

### 🔹 Laptops

* Price
* Rating
* Reviews
* RAM
* Processor generation
* Screen size
* Brand

### 🔹 Washing Machines

* Price
* Rating
* Reviews
* Discount
* Speed (RPM)
* Weight (kg)
* Warranty
* Brand

---

## 📈 Key Insights

### Laptop Analysis

* Most laptops are priced between **₹40,000 – ₹80,000**
* Higher RAM is associated with **higher prices**
* RAM and price show a **positive correlation**
* Screen size and price have a **weak positive correlation**
* Rating and price show a **moderate positive correlation**
* Lower-priced laptops receive **more reviews**
* Most laptops belong to the **Intel i5 series**

### Washing Machine Analysis

* Most washing machines are priced between **₹10,000 – ₹20,000**
* Ratings mostly lie between **4.2 – 4.4**
* Speed around **800 RPM** is most common
* Typical weight is around **7 kg**
* Common warranty period is **2 years**
* Price and rating show a **weak positive correlation**
* Discount and rating show a **negative correlation**

---

## 📉 Visualizations Included

* Price distribution plots
* Violin plots for price and rating
* Correlation heatmaps
* Company-wise comparisons
* Price vs Rating & Reviews plots

---

## ⚠ Disclaimer

This project is created **strictly for educational and learning purposes**.
The scraped data belongs to Flipkart, and their **terms & conditions** should be respected.

---

## 🚀 Future Improvements

* Add more product categories
* Automate periodic price tracking
* Store data in a database
* Build an interactive dashboard

---

## 👤 Author

Vikash A   
Aspiring Data Scientist


---
