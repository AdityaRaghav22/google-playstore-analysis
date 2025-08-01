# 📊 Google Play Store Data Analysis

This project performs an **Exploratory Data Analysis (EDA)** on a dataset of Google Play Store applications. The goal is to uncover trends, patterns, and insights related to app categories, installs, reviews, ratings, and pricing models.

---

## 📁 Project Structure
├── dataset/ # Raw and cleaned dataset CSV files
├── notebooks/ # Jupyter notebooks with EDA code
├── insights.md # Extracted insights from analysis
├── final_summary_report.md # Polished report for quick review
├── visuals/ # PNG images of key plots/graphs
├── requirements.txt # Required Python packages
└── README.md # Project description (this file)


---

## 🎯 Objectives

- Clean and preprocess real-world app data from the Google Play Store
- Analyze distributions of ratings, installs, and prices
- Compare free vs. paid apps by performance
- Visualize trends across app categories
- Provide actionable insights in a summary report

---

## 🧹 Data Cleaning

The dataset had several issues that were fixed:
- Removed duplicate and null entries
- Converted `Installs`, `Reviews`, and `Price` columns to numeric
- Standardized categories and types
- Dropped outlier values and corrected column formats

---

## 📊 Key Insights

Here are a few important findings:

- 🎮 **Game apps** are the most downloaded, with **~12.82 billion installs**, making up **~37.3%** of all installs.
- 🆓 **Free apps** dominate the market, making up **~92.4%** of all apps.
- 📰 **GAME** and **FAMILY** also show high install rates.
- 🛠️ **Underperformers**: SOCIAL & NEWS_AND_MAGAZINES apps have low install and engagement.
Read all insights in [`insights.md`](./insights.md)

---

## 📈 Visualizations Included

- Top 10 Categories by Total Installs
- Rating Distribution by App Type (Free/Paid)
- Category-wise Install Count

Visuals are stored in the `visuals/` folder for easy access.

---

## 🛠 Tech Stack

- Python 3.9+
- Jupyter Notebook
- Pandas & NumPy for data processing
- Matplotlib & Seaborn for visualization

---

## ✅ Deliverables
✅ Cleaned dataset for analysis

✅ EDA notebook with step-by-step analysis

✅ Summary report: final_summary_report.md

✅ Insights file: insights.md

✅ Visuals for presentation

## 🙋‍♂️ Author
Aditya Raghav
🔗 GitHub (https://github.com/AdityaRaghav22) | 🔗 LinkedIn (https://www.linkedin.com/in/aditya-raghav-7893392a4/)

## 📄 License
This project is released under the MIT License.
The dataset used is for educational purposes only and was sourced from Kaggle.

