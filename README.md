# 🍽️ Zomato Data Analysis

## 📌 Project Overview
This project analyzes Zomato restaurant data to uncover patterns in customer preferences, restaurant popularity, and service offerings.  
It combines **data cleaning, feature engineering, visualization, and clustering** to provide actionable insights into the food industry.

---

## 🛠️ Features & Workflow

1. **Data Preprocessing**
   - Removed missing values and duplicates.
   - Cleaned columns (ratings, cost, etc.).
   - Standardized formats for analysis.

2. **Feature Engineering**
   - `cost_per_person` → derived from cost for two.
   - `online_delivery_flag` and `book_table_flag` → converted into binary indicators.
   - `rating_category` → grouped into Poor, Average, Good, Excellent.

3. **Exploratory Data Analysis (EDA)**
   - Distribution of ratings, costs, and votes.
   - Restaurant type frequency analysis.
   - Impact of online delivery and table booking.

4. **Correlation Analysis**
   - Heatmap to visualize relationships between cost, votes, ratings, and service flags.
   - Found strong relation between votes and ratings, weaker link between cost and ratings.

5. **Clustering**
   - Applied **KMeans clustering** on cost, ratings, votes, and engineered features.
   - Segmented restaurants into meaningful groups (Budget, Mid-range Popular, Premium, Mixed).

6. **Visualization**
   - Used **Seaborn & Matplotlib** for static plots.
   - Extended with **interactive visualizations (Plotly)** for deeper exploration.

---

## 📊 Key Insights
- Higher cost does not guarantee higher ratings.
- Popular restaurants (more votes) tend to have higher ratings.
- Online delivery and table booking improve customer engagement but aren’t the only factors.
- Restaurant clusters reveal **different market segments**: affordable popular spots vs luxury fine dining.

---

## 🚀 Future Enhancements
- Sentiment analysis using customer review text (if available).
- Dashboard development using **Streamlit/Dash** for interactive exploration.
- Time-series analysis if timestamped review data is obtained.

---

## 📂 Repository Structure
