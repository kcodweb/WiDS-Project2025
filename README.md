# WiDS – Predictive Customer Analytics: CLV Forecasting & Behavioral Segmentation Using RFM Methodology

**Endterm Project – Karan Bansal (24b3003)**

This repository contains an end-to-end predictive customer analytics project focused on understanding customer behavior, estimating customer lifetime value (CLV), and predicting customer churn using machine learning models. The project demonstrates how real-world transactional data can be transformed into actionable business insights for customer segmentation, retention, and strategic decision-making.

---

## Project Overview

The objective of this project is to:

* Clean and preprocess customer transaction data
* Perform exploratory data analysis (EDA)
* Segment customers using RFM (Recency, Frequency, Monetary) analysis
* Estimate Customer Lifetime Value (CLV)
* Predict customer churn using multiple machine learning models
* Compare and rank models based on performance
* Translate analytical results into business strategies

---

## Dataset

The dataset used is the online_retail_data.xlsx, which contains transactional data from a UK-based online retail company.

## Repository Structure

```
WiDS-Project2025/
│
├── 24b3003_Report.pdf          # Final endterm report
├── CustomerAnalytics_EDA.ipynb # EDA and data preprocessing
├── Modeling.ipynb             # RFM, CLV, churn modeling
├── cleaned_data.csv           # Cleaned transaction data
├── final_customer_analytics.csv # Final customer-level dataset
├── online_retail_data.xlsx    # Raw dataset
└── README.md                  # Project description
```
---

## Models Used

The following machine learning models were used for churn prediction:

* Logistic Regression
* Random Forest
* Decision Tree
* K-Nearest Neighbors (KNN)
* Gradient Boosting

Models were evaluated using Accuracy, Precision, Recall, F1-score, and ROC-AUC.

---

## Key Outputs

* **cleaned_data.csv:** Cleaned transactional dataset
* **final_customer_analytics.csv:** Customer-level dataset with RFM, CLV, churn labels, and segmentation
* **24b3003_Report.pdf:** Complete project report with analysis and business insights

---
