# Retail-Customer-Behavior-Analysis

## Overview

This project focuses on enhancing e-commerce sales strategies by leveraging customer behavior data. We developed an end-to-end pipeline involving anomaly detection, customer segmentation, and smart product recommendation using NLP. The goal was to understand customer actions, identify valuable user groups, remove fraudulent activities, and ultimately optimize sales through data-driven decisions.

---

## Problem Statement

**How can we improve sales on an e-commerce platform?**

We explored multiple strategies:

- Recommending products based on purchase history
- Targeted promotions for high-value customers
- Detecting and removing fraudulent users
- Improving search result relevance
- Identifying top-performing products in each category

---

## Tech Stack

- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- PyCaret, BERT Transformers
- NLP (TF-IDF, Embeddings)
- Isolation Forest, PCA
- K-Means Clustering
- Google Colab / Jupyter

---

## Methodology

### Market Basket Analysis & Anomaly Detection

- **Spearheaded anomaly detection** using Isolation Forest and PCA to find and remove unusual transactions.
- This resulted in a **50% improvement in the quality of product bundles** created.
- Used **Variation Inflation Factor (VIF)** to address multicollinearity in browsing and purchasing behaviors.

### Customer Segmentation using K-Means

- Performed batch processing and stabilized K-means with statistical evaluation (Elbow method and iterative refinement).
- **Identified two customer clusters**:
  - **Cluster 0**: High-value, engaged users
  - **Cluster 1**: Window shoppers or less active users
- These insights enable tailored marketing (e.g., A/B testing with personalized offers).

### NLP-Based Product Recommendation Engine

- Built a recommendation engine using **BERT Transformers** and recency-weighted product reviews.
- Considered both product descriptions and time-weighted reviews to retrieve **top 10 relevant products**.
- Designed to optimize product discovery and increase conversions.

---

## Real-World Applications

- Fraud detection using PCA reconstruction error and Isolation Forest
- Personalized marketing and promotions based on user clusters
- NLP-driven product search and recommendation
- Highlighting best sellers in each product category

---

## Future Work

- Hyperparameter tuning of Isolation Forest contamination levels
- Incorporating number of reviews into query relevance scoring
- Topic summarization of customer reviews for better recommendation explanations

---

## Conclusion

This project successfully:

- Enhanced product bundling through anomaly filtering
- Segmented users for more precise marketing
- Built an effective, recency-aware product recommendation system
- Flagged abnormal behaviors and potential bots
- Identified top-performing products across categories


