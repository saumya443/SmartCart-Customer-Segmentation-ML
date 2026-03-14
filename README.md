# 🛒 SmartCart: Data-Driven Customer Segmentation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/ML-Clustering-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📌 Project Overview
SmartCart ek growing e-commerce platform hai jo multiple countries mein operate karta hai. Pehle, company sabhi customers ke liye ek hi generic marketing strategy use karti thi, jiske karan high-value customers retain nahi ho pa rahe the. 

Is project mein maine **Unsupervised Machine Learning** ka use karke 2240 customers ko unke behavior aur demographics ke basis par **4 distinct clusters** mein segment kiya hai.

---

## 🚀 Problem Statement
Generic marketing ki wajah se SmartCart ko ye nuksan ho rahe the:
* **Missed Opportunities:** High-value customers ko identify nahi kar pa rahe the.
* **Customer Churn:** Wo users jo platform chhodne wale the, unka pata nahi chal raha hai.
* **In-efficient Marketing:** Marketing budget galat jagah kharch ho raha tha.

---

## 🛠️ Technical Workflow

### 1. Data Exploration (EDA)
Maine 22 attributes ko analyze kiya, jisme income, spending habits (Wine, Fruits, Meat, etc.), aur campaign responses shamil hain.

### 2. Feature Engineering & Preprocessing
* **New Features:** Age aur Total Spending jaise naye columns calculate kiye.
* **Scaling:** `StandardScaler` ka use karke data ko normalize kiya taaki clustering accurate ho.

### 3. Model Building
Maine **KNN** aur **Agglomerative Clustering** dono ko try kiya.
* **Agglomerative Clustering** ne hierarchical patterns ko zyada behtar tarike se capture kiya.
* **Optimal Clusters:** Dendrogram analysis ke baad maine **4 clusters** finalize kiye.



---

## 📊 Cluster Insights
Segmentation ke baad humne customers ko 4 categories mein baanta:
1. **Cluster 0 (Elite):** High spending, frequent buyers (Loyalists).
2. **Cluster 1 (At-Risk):** Purane customers jo ab inactive ho rahe hain.
3. **Cluster 2 (Deal Seekers):** Sirf discounts aur deals par kharidari karne wale.
4. **Cluster 3 (New/Low Engagement):** Naye users jinhe engagement ki zaroorat hai.



---

## 📂 Repository Structure
```text
├── smartcart.ipynb          # Full Jupyter Notebook with EDA and Modeling
├── smartcart_customers.csv  # Dataset used for the project
└── README.md                # Project Documentation
