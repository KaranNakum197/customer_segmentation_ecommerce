# 🛍️ Customer Segmentation for E-Commerce

## 📌 Project Overview

This project applies **unsupervised learning** techniques to segment customers of an e-commerce company based on their purchasing behavior. Using **clustering algorithms**, we aim to identify meaningful customer segments to help the company develop more effective, targeted marketing strategies.

---

## 🎯 Problem Statement

An e-commerce company wants to segment its customers into meaningful groups based on their transaction patterns. You are provided with customer transaction data. Your task is to:
- Clean and preprocess the data
- Engineer features such as RFM (Recency, Frequency, Monetary)
- Apply clustering techniques (K-Means)
- Analyze and label clusters for marketing insights

---

## 📂 Dataset

- **Source:** Online Retail Dataset ([UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail)) or Kaggle version
- **Description:** This dataset contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based online retail company.

---

## ✅ Tasks Completed

### 1. 📥 Data Collection & Preprocessing
- Loaded dataset using Pandas
- Removed null values and duplicates
- Filtered out canceled/returned orders (negative quantities)
- Converted `InvoiceDate` to datetime format
- Encoded categorical features (e.g., Country)
- Applied feature scaling using `StandardScaler`

### 2. 📊 Exploratory Data Analysis (EDA)
- Analyzed customer behavior:
  - Total spend
  - Transaction frequency
  - Recency of purchases
- Visualized patterns using:
  - Histograms
  - Box plots
  - Scatter plots

### 3. 🧮 Feature Engineering
- Created **RFM features**:
  - **Recency:** Days since last purchase
  - **Frequency:** Number of purchases
  - **Monetary:** Total amount spent
- (Optional) Applied **PCA** for dimensionality reduction

### 4. 🤖 Model Building
- Applied **K-Means Clustering**
  - Used **Elbow Method** to choose optimal `k`
  - Clustered customers into segments

### 5. 📈 Evaluation & Business Insights
- Identified key customer segments:
  - 🎯 **High-Value Frequent Buyers**
  - 🔁 **Frequent Low-Spenders**
  - 💤 **Inactive Customers**
- Provided **business recommendations**:
  - Target high-value customers with loyalty programs
  - Re-engage dormant customers with special offers
  - Promote upselling to frequent low-spending customers

---
