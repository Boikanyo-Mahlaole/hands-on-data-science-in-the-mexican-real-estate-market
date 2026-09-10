# hands-on-data-science-in-the-mexican-real-estate-market
Hands-on data science in the mexican real estate market using numpy, pandas, matplotlib- WQU data science modeling badge.
# Project 1: Housing in Mexico 🇲🇽
## WorldQuant University — Applied Data Science Lab

## 📌 Project Overview
This project kicks off the foundational workflow of data science by investigating the real estate market in Mexico. The core objective is to analyze a dataset of over 21,000 property listings to answer a fundamental market question: **What has a greater impact on real estate prices in Mexico — location or property size?**

Through this project, we explore tabular data, clean real-world structural data, handle messy missing fields, and apply statistical tools like correlation and price per square meter to extract meaningful real estate patterns.

## 📊 Key Research Questions
1. How does the **price per square meter** vary across different states and regions in Mexico?
2. Is there a strong **correlation** between property size (surface area) and its sale price?
3. Does **location** (geography/state) play a more dominant role in driving property costs than the physical size of the asset itself?

## 🛠️ Tech Stack & Skills Highlighted
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Core Concepts:**
  - Tabular Data Organization (Lists & Dictionaries)
  - Data Wrangling & Outlier Trimming
  - Exploratory Data Analysis (EDA)
  - Feature Engineering (Calculating `price_per_m2`)
  - Statistical Correlation & Aggregations (`groupby`, `mean`)

## 📁 Repository Structure
- `011-tabular-and-tidy-data.ipynb`: Organizing messy input data and building basic python structures.
- `012-data-wringing-pandas.ipynb`: Importing CSV datasets, filtering specific subsets, and handling null entries.
- `013-exploratory-data-analysis.ipynb`: Utilizing descriptive statistics and generating initial distributions.
- `014-location-or-size.ipynb`: Analyzing correlations, grouping metrics by state, and drafting the final verdict.

## 📈 Key Findings & Insights
- **The Metric Shift:** While initial checks might suggest certain states look more expensive on average, calculating the **price per square meter** paints a much more accurate economic picture. For instance, Mexico City (*Distrito Federal*) consistently yields premium pricing per square meter compared to states with larger overall plot sizes.
- **Size vs. Price Correlation:** There is a moderate positive correlation between a property’s surface area and its price nationwide. However, this relationship behaves dynamically across boundaries; some states show a rigid link between size and price, whereas premium markets are driven heavily by location and localized demand.

## 🚀 Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Open Jupyter Lab/Notebook and step through the project folders to review the workflow.

***
*Note: This project is part of the credentialed Applied Data Science Lab curriculum provided by [WorldQuant University](https://www.wqu.edu/).*
