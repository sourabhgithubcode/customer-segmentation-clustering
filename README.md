# From Clicks to Conversions: 4-Cluster Segmentation of 12K+ Sessions Achieving 99% Precision in Purchase Prediction

1. E-commerce sites lose most visitors before they buy, so knowing who will convert matters for ad spend, bounce reduction, and campaign ROI. I analyzed 12,330 shopping sessions to predict purchase intent and segment users.
2. In R, I cleaned skewed data with log transforms and IQR capping, oversampled the minority class, engineered features like ProductEngagement bins, and used K-Means (k=4) to find customer segments before classification.
3. I compared SVM and Decision Tree with 5-fold cross-validation. SVM reached 98.99% accuracy and 0.999 AUC. Cluster 3 converted at 30.5% versus 0.65% for Cluster 1, which supports targeting and ad-exclusion strategies.
4. Key lessons: accuracy alone misleads, clustering informs supervised modeling, and suspiciously high scores demand leakage checks. Next steps are a Flask API, XGBoost comparison, and an interactive dashboard.


## 📊 Meaning customer Intentions clusters 

<img width="799" height="557" alt="Screenshot 2026-01-01 at 8 18 24 PM" src="https://github.com/user-attachments/assets/1962a63e-0fde-4ecd-8aa9-18194f6d6727" />


## 📦 Installation & Run
```R
# In RStudio or R console
source("OSI_analysis.R")
```

## 📄 License
MIT
