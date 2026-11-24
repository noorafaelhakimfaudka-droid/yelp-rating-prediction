# Yelp Restaurant Rating Prediction

An end-to-end regression analysis and machine learning project predicting Yelp business star ratings (`1.0` to `5.0`) by integrating multi-table relational data across businesses, user reviews, check-ins, tips, and photos.

## Project Overview
* **Objective:** Identify key behavioral and review-level drivers behind business ratings and build a predictive regression model.
* **Dataset:** Yelp Open Dataset (~188,593 business records merged across 6 JSON tables using `business_id`).
* **Tech Stack:** Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn.

## Repository Structure
```text
yelp-rating-prediction/
├── assets/
│   └── model_evaluation.png       # Actual vs. Predicted & Feature Importance plots
├── data/                          # Local directory for raw Yelp JSON files (gitignored)
├── notebooks/
│   └── yelp_rating_regression.ipynb
├── .gitignore
├── requirements.txt
└── README.md