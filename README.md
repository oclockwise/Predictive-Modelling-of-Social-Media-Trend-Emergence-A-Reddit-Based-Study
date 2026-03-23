# Predictive Modelling of Social Media Trend Emergence (Reddit-Based Study)

## Overview
This project explores how viral content emerges on Reddit using data analytics and machine learning. The goal is to identify key factors influencing engagement and predict whether a post will become viral.

## Dataset
- Source: Reddit dataset (Kaggle)
- Features include:
  - Post title & content
  - Upvotes (engagement)
  - Timestamp (temporal data)
  - Subreddit (community data)

## Methodology
- Data Cleaning & Preprocessing
- Feature Engineering:
  - TF-IDF (text features)
  - Sentiment analysis
  - Temporal features (hour, weekday)
  - Community-level features
- Models Used:
  - Logistic Regression (classification)
  - Random Forest / XGBoost
  - Regression models (engagement prediction)
  - ARIMA (time-series forecasting)

## Key Findings
- Text content, timing, and subreddit activity influence engagement
- Models can reasonably predict viral posts
- Sudden spikes in engagement remain challenging to predict

## Tools & Technologies
- Python (Pandas, NumPy)
- Scikit-learn
- XGBoost
- Statsmodels (ARIMA)
- Jupyter Notebook

## Future Improvements
- Use real-time Reddit API data
- Apply deep learning models (e.g., BERT)
- Include user interaction networks

## 👤 Author
Jolin
