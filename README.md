# Zomato Restaurant Analysis & Dining Rating Prediction

Exploratory data analysis and machine learning on Bangalore and Pune restaurant data to predict dining ratings.

**Published Research:** [Journal of Advanced Research in Machine Learning](https://zenodo.org/records/10565792)

---

## Tools Used
- **Python** — Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning** — Scikit-learn (Random Forest Regressor)
- **Stats** — Scipy, Statsmodels

---

## Dataset
- Two datasets merged — Bangalore and Pune restaurants
- Fields: Restaurant Name, Category, Pricing for 2, Dining Rating, Delivery Rating, Review Counts, Locality, Coordinates

---

## What Was Done

**Data Cleaning**
- Merged Bangalore and Pune datasets on common identifiers
- Handled missing values — filled with mean for numeric columns
- Removed duplicates and irrelevant columns

**Exploratory Data Analysis**
- Distribution of dining and delivery ratings
- Most famous restaurant chains (top 20)
- Pricing distribution across restaurants
- Expensive vs cheapest restaurants identified
- Correlation between delivery rating and dining rating

**Key Finding**
- Significant positive correlation between delivery rating and dining rating — restaurants with higher delivery ratings also tend to have higher dining ratings

**Machine Learning**
- Model: Random Forest Regressor
- Target: Dining Rating prediction
- Features: Dining Review Count, Delivery Rating, Pricing for 2
- Train/Test split: 80/20



## Publication
This project was published in the **Journal of Advanced Research in Machine Learning and Artificial Intelligence.**
[View Publication](https://zenodo.org/records/10565792)
