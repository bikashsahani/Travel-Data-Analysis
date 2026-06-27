# Travel-Data-Analysis
This repository contains Travel Data Analysis workflow to uncover insights into traveler behaviors, preferences, and trends. Utilizing dataset of global trips, explores relationships between traveler demographics, trip specifics (destinations, dates, duration), and financial factors (accommodation and transportation types/costs).

# Travel Data Analysis Project
An end-to-end exploratory data analysis (EDA) and data manipulation project utilizing Python, Pandas, Seaborn, and Matplotlib. This project investigates global travel trends, spending behaviors across demographics, transportation preferences, and seasonal trip patterns.

## Project Overview
The objective of this project is to clean, manipulate, and visualize a comprehensive travel dataset to uncover hidden patterns regarding where people travel, how much they spend, and what factors most heavily influence the total cost of a trip. 

### Key Business Questions Answered:
* What are the top travel destinations globally?
* How do trip costs spread across different accommodation types?
* Does traveler demographics (age/gender) impact spending patterns?
* Which factors possess the strongest statistical correlation with total trip costs?
* Are there definitive seasonal peaks in global travel?

---

## Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## Key Insights & Findings

### 1. Data Engineering & Cost Structure
* Engineered a tracking `Total cost` feature ($Accommodation\ cost + Transportation\ cost$).
* Discovered that **Cost per day** ($0.9807$) and **Accommodation cost** ($0.9805$) have an incredibly strong positive linear correlation with the `Total cost`, making them the most critical financial predictors.

### 2. Accommodation & Spending Variability
* **Widest Cost Spread:** **Resorts** exhibit the highest structural price variability (widest Interquartile Range and whisker spread), representing options ranging from budget getaways to high-end luxury.
* **Outlier Spikes:** While **Hotels** and **Airbnbs** have tighter core distribution boxes, they contain extreme luxury outliers peaking near $10,000+.

### 3. Demographic Analysis
* **Do older people spend more?** Yes. The **Senior** group holds a noticeably higher median trip cost (approx. $1,800) than both the Middle and Young age groups. However, their spending is highly predictable with zero extreme outliers. 
* **Accommodation Preference by Gender:** Grouped analysis indicates specific distribution variations between male and female traveler choices across vacation rentals, hotels, and hostels.

---
## Files
- Travel_data_analysis.ipynb    — Main EDA notebook
- Travel details dataset.csv     — Raw dataset
- Cleaned_Travel_data.csv        — Cleaned output

## 👤 Author
Bikash Sahani
github.com/bikashsahani | linkedin.com/in/bikash-sahani