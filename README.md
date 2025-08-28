
 COVID-19 Data Analysis (EDA Project):

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on COVID-19 global data to understand the **spread, impact, and patterns** of the pandemic across different countries and regions.

The goal is to generate insights into:

* Country-wise confirmed, deaths, and recoveries
* Fatality and recovery rates
* Region-wise comparisons
* Correlation between COVID-19 metrics
* Outlier countries with unusual trends
* Visualizations for better storytelling

---

## 📂 Dataset

* **Source:** \[COVID-19 Global Data (Kaggle / WHO / Johns Hopkins)]
* **Columns Included:**

  * `Country/Region` – Name of the country
  * `Confirmed` – Total confirmed cases
  * `Deaths` – Total deaths
  * `Recovered` – Total recoveries
  * `Active` – Active cases
  * `New cases`, `New deaths`, `New recovered` – Daily updates
  * `Deaths / 100 Cases`, `Recovered / 100 Cases` – Ratios
  * `WHO Region` – Region classification

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries Used:**

  * `pandas`, `numpy` → Data wrangling
  * `matplotlib`, `seaborn` → Static plots
  * `plotly` → Interactive visualizations
  * `scikit-learn` → Clustering analysis

---

## 📊 Analysis & Visualizations

### ✅ Basic EDA

* Summary statistics
* Missing values check
* Country & region distributions

### ✅ Advanced Insights

1. **Top 20 Countries** with most cases
2. **Correlation Heatmap** of COVID-19 metrics
3. **Active vs New Cases** (outbreak trend check)
4. **Case Fatality Ratios** by WHO region
5. **Pareto Analysis (80/20 Rule)** → How few countries dominate case counts
6. **Bubble Map (Geo Visualization)** for global spread 🌍
7. **Clustering Analysis (KMeans)** → Grouping countries with similar patterns
8. **Outlier Detection** → Countries with unusual fatality/recovery trends

---

## 📈 Sample Visuals

* Choropleth map of confirmed cases by country
* Heatmap showing correlations among features
* Scatter plots (Active vs New Cases)
* Interactive bar charts (Region-wise death rates)
* Clustering visualization



