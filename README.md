# 🛒 eCommerce Customer Behaviour Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue)
![ML](https://img.shields.io/badge/ML-KMeans%20Clustering-orange)
![PCA](https://img.shields.io/badge/Dimensionality-PCA-purple)
![Dataset](https://img.shields.io/badge/Dataset-800%20Responses-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> *"Who are eCommerce customers — and what drives their shopping behaviour?"*  
> This project segments online shoppers into distinct personas using unsupervised ML.

---

## 🎯 Objective

Analyse eCommerce customer shopping behaviour survey data to uncover patterns in 
purchasing habits, browsing behaviour, review engagement, and personalisation 
preferences — and segment customers into meaningful clusters using KMeans and PCA.

---

## 📦 Dataset

| Detail | Value |
|--------|-------|
| Source | eCommerce Customer Shopping Behaviour Survey |
| Records | 800 survey responses |
| Features | 24 columns |
| Data Type | Mixed — categorical and numerical |

**Key Features:**
- Purchase frequency and product categories
- Browsing and product search behaviour
- Cart behaviour and abandonment factors
- Review engagement and reliability
- Personalised recommendation preferences
- Shopping satisfaction and service appreciation

---

## ⚙️ Analysis Pipeline

1. **Data Cleaning** — Null handling, mode imputation, inconsistent format resolution
2. **Feature Engineering** — Label encoding for categorical features
3. **Exploratory Data Analysis** — Distribution analysis across all 24 features
4. **Dimensionality Reduction** — PCA to reduce feature space for clustering
5. **Customer Segmentation** — KMeans clustering with Silhouette Score optimisation
6. **Cluster Profiling** — Characterising each customer segment

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3.11 | Core programming |
| Pandas, NumPy | Data manipulation |
| Matplotlib, Seaborn | Visualisation |
| Scikit-learn | PCA, KMeans, Label Encoding, Silhouette Score |
| SciPy | Statistical analysis |

---

## 📁 Project Structure

    eCommerce-Customer-Behaviour-Analysis/
    ├── ecommerce_customer_behaviour_analysis.ipynb   # Main analysis notebook
    ├── eBay.csv                                       # Survey dataset (800 responses)
    └── README.md

---

**Author:** Anjana Ambika | **Date:** January 2026
