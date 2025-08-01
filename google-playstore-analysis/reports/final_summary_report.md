
# Google Play Store Data Analysis – Final Report

## 📌 Objective
To analyze app data from the Google Play Store and derive meaningful insights for app developers, marketers, and investors.

## 📊 Dataset Overview
- Total Apps: 10,000+
- Features: Category, Rating, Reviews, Size, Installs, Type, Price, Content Rating, etc.
- Source: [https://www.kaggle.com/datasets/lava18/google-play-store-apps]

## 🧹 Data Cleaning
- Removed duplicates
- Fixed missing values in `Rating`, `Size`, etc.
- Standardized `Installs`, `Size` units
- Converted `Price` to numeric

## 📈 Key Analyses
- Category distribution
- Rating and Review correlations
- Install trends
- Free vs Paid apps
- Top apps by installs and ratings

## 📌 Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Power BI (Dashboard)
- Jupyter Notebook

## 📌 Key Findings
- Most apps are free (92%)
- GAME and FAMILY have highest installs
- Paid apps don’t always have better ratings
- App size has a weak correlation with rating


## 📌 Conclusion
Google Play Store is dominated by free apps, and having more installs doesn't always mean higher ratings. Developers should focus on app quality and user reviews for better engagement.