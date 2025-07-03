#Market_Data_Analysis
📊 Facebook Live Sellers & Advertising Sales Prediction - Data Analysis Project

This project contains detailed exploratory data analysis (EDA), visualization, and predictive modeling for two real-world datasets:

1. **Facebook Live Sellers in Thailand**  
2. **Advertising Expenditure vs Product Sales**

These datasets were analyzed as part of a case project, with each dataset addressed separately in its own Jupyter Notebook. The project aims to uncover insights from social media engagement patterns and understand how advertising spend affects product sales.

---------------------------
📌 Dataset 1: Facebook Live Sellers in Thailand

**Objective:**  
Analyze how post timing, type, and engagement metrics like reactions, shares, and comments interact. Identify posting strategies that maximize engagement and cluster posts by behavior.

**Highlights:**
- Cleaned and processed timestamp and engagement fields.
- Analyzed average reactions by hour of day.
- Explored correlations between reactions, shares, and comments.
- Compared engagement by post type (status, video, photo, link).
- Applied K-Means clustering (using PCA) to group posts by engagement patterns.

**Visualizations:**
- Line plots for hourly engagement trends
- Heatmaps for correlation matrices
- Cluster analysis using PCA-reduced components

--------------------------

📌 Dataset 2: Advertising Spend vs Sales

**Objective:**  
Build a regression model to predict product sales based on advertising spend across TV, Radio, and Newspapers.

**Key Analysis:**
- Performed EDA on 150 entries of ad spend and sales data.
- Calculated Pearson correlation between each ad channel and sales.
- Trained and evaluated a multiple linear regression model.
- Identified the most impactful advertising channels.

**Findings:**
- TV and Radio show strong positive correlation with sales.
- Newspaper has low predictive power.
- Model achieved high R² score using only TV and Radio features.



## 🚀 Getting Started

### Prerequisites
If running locally, install required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

