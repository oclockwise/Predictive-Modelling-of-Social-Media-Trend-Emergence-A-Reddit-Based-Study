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

### Machine Learning Models
- Logistic Regression (classification)
- Random Forest / XGBoost
- Regression models (engagement prediction)

### Time-Series Analysis
- Weekly aggregation of engagement
- ARIMA model for trend forecasting

### Network Analysis
- Constructed a subreddit similarity network based on content features
- Applied centrality measures (degree, betweenness)
- Analysed relationships between network position and viral engagement

## Key Findings
- Text content, timing, and subreddit activity influence engagement
- Network centrality shows weak correlation with viral rate
- Models can reasonably predict viral posts
- Sudden spikes in engagement remain challenging to predict

## Tools & Technologies
- Python (Pandas, NumPy)
- Scikit-learn
- XGBoost
- Statsmodels (ARIMA)
- NetworkX (network analysis)
- Jupyter Notebook

## Future Improvements
- Use real-time Reddit API data
- Apply deep learning models (e.g., BERT)
- Improve network modelling with user interaction graphs

## Author
Jolin
