# Sugarcane Production Data Analysis

This repository contains a Jupyter Notebook that analyzes global sugarcane production data using Python and popular libraries like **Pandas**, **Seaborn**, and **Matplotlib**.

The dataset used is: **`List of Countries by Sugarcane Production.csv`**.

---

## 📁 Contents

- `Sugarcane Analysis.ipynb` – Main notebook for data cleaning, exploration, and visualization
- `List of Countries by Sugarcane Production.csv` – Dataset used in the analysis
- `README.md` – Project overview and documentation

---

## 🧹 Data Cleaning

The dataset required some preprocessing:

- Removed unwanted characters (e.g., commas, dots) from numeric columns
- Dropped irrelevant or non-informative columns
- Acknowledged minor `FutureWarning`s that do not impact results

---

## 📈 Univariate Analysis

Explores each variable individually using:

- **Bar plots**
- **Distribution plots**

Focuses on identifying data distributions, skewness, and outliers.

---

## 🔄 Bivariate Analysis

Investigates relationships between two variables, such as:

- **Land Area vs. Total Production**
- **Yield per Hectare vs. Total Production**

Visualization tools used:

- **Scatterplots**
- **Bar plots**

---

## 📊 Correlation Analysis

A heatmap is used to visualize the correlation matrix among numerical variables, helping to identify strong or weak linear relationships.

---

## 🌍 Analysis by Continent

Compares sugarcane production metrics across continents to uncover regional patterns and trends.

Tools used:

- **Bar plots**
- **Line plots**

---

## ✅ Conclusion

This analysis reveals key insights into global sugarcane production:

- Highlights top-producing countries
- Uncovers correlations and productivity trends
- Shows regional disparities in output and efficiency

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sugarcane-analysis.git
