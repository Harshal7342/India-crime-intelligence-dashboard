# 🇮🇳 India Crime Intelligence Dashboard (2001–2013)

A data analytics project exploring district-level crime patterns in India using **Python (Pandas, NumPy, Matplotlib, Seaborn)** and **Power BI**.

This project analyzes historical crime data to uncover trends, high-crime regions, dominant crime categories, and long-term growth patterns.

---

## 📌 Project Objective

The goal of this project is to:

- Analyze crime distribution across Indian states and districts
- Identify states with highest reported crimes
- Understand crime trends from 2001 to 2013
- Detect crime categories with highest growth
- Visualize insights using interactive Power BI dashboards

---

## 🛠 Tools & Technologies Used

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Power BI**
- Git & GitHub
- Jupyter Notebook

---

## 📂 Project Structure

```
india-crime-intelligence-dashboard/
│
├── dashboards/
│   └── crime_intelligence_dashboard.pbix
│
├── data/
│   ├── raw/
│   │   └── Crimes_in_india_2001-2013.csv
│   └── cleaned/
│       └── clean_crime_data.csv
│
├── images/
│   ├── crime_overview.png
│   ├── crime_category.png
│   └── crime_map.png
│
├── notebooks/
│   └── crime_analysis.ipynb
│
├── README.md
└── requirements.txt
```
---

## 🔎 Data Cleaning Process

- Removed summary rows such as `TOTAL` and `ZZ`
- Standardized state names
- Aggregated crime totals at state and district levels
- Created a cleaned dataset for Power BI

Cleaned dataset exported as: data/cleaned/clean_crime_data.csv


---

## 📊 Key Insights

- 📈 Crime levels steadily increased between 2001 and 2013
- 🏙 Large states such as Madhya Pradesh and Maharashtra recorded the highest crime totals
- 🚗 Property crimes (theft, auto theft) dominate overall statistics
- 🌆 Major metropolitan districts report highest crime volumes
- 🔺 Certain crime categories experienced significant growth over the period

---

## 📈 Dashboard Preview

### 📈 State-Level Overview
![Crime Overview](images/crime_overview.png)

### 📊 Crime Category Analysis
![Crime Category](images/crime_category.png)

### 🗺 Crime Distribution Map
![Crime Map](images/crime_map.png)


---

## 🚀 How to Run This Project

1. Clone the repository: git clone https://github.com/Harshal7342/india-crime-intelligence-dashboard.git

2. Install dependencies: pip install -r requirements.txt

3. Open the Jupyter notebook: notebooks/crime_analysis.ipynb

4. Open Power BI dashboard: dashboards/crime_intelligence_dashboard.pbix

---

## ⚠ Dataset Limitation

The dataset includes crime records up to **2013**.  
Although historical, this data helps analyze long-term crime trends and understand structural patterns in crime distribution.

---

## 📌 Future Improvements

- Add population-adjusted crime rate analysis
- Integrate updated crime data (post-2013)
- Deploy dashboard to Power BI Service
- Add predictive modeling using machine learning

---

## 👨‍💻 Author

**Harshal Mahajan**  
Aspiring Data Analyst | Python | Power BI  
