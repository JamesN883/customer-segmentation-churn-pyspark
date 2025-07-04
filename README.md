# Customer Segmentation and Churn Prediction with PySpark

## 📌 Overview
This project showcases the use of **Apache Spark (PySpark)** for scalable customer analytics. It implements a full pipeline for:
- 📈 **Customer segmentation** using RFM metrics and K-Means clustering
- 🔍 **Churn prediction** using Random Forest and Gradient Boosting Trees
The aim is to support **data-driven marketing** and **customer retention strategies** at scale.

## 🗂️ Dataset
**Source**: [Online Retail (Chen, 2015)](https://archive.ics.uci.edu/ml/datasets/Online+Retail)  
**Description**:  
- Transactional data from a UK-based online retailer (Dec 2010 – Dec 2011)  
- 541,909 rows × 8 variables  
- Focuses on wholesale customers with behavior-based signals

## ⚙️ Workflow
1. **Data Preprocessing & Cleaning**
2. **Feature Engineering:**
   - Derivation of RFM (Recency, Frequency, Monetary) metrics
3. **Customer Segmentation:**
   - K-Means Clustering with WCSS and Silhouette Score optimization
4. **Churn Prediction:**
   - Random Forest and Gradient Boosting classifiers
   - Includes hyperparameter tuning and cross-validation

## 🛠️ Tools & Technologies
- Apache Spark (PySpark)
- MLlib (for machine learning)
- Google Colab (for orchestration and analysis)

## 📊 Results
- Achieved **98% classification accuracy** with high AUC ≈ 0.997
- Effective segmentation of customer groups for targeted strategies
- Demonstrated end-to-end scalable modeling on semi-large datasets

## ⚠️ Challenges
- Long training time (~4 hours) for ensemble models in PySpark on a single machine
- Lack of distributed infrastructure limited speed and experimentation

## 🔭 Future Work
- ⚙️ **Distributed Training** using HDFS and Spark clusters to improve scalability
- 🔄 **Real-Time Prediction** via streaming pipelines for up-to-date churn detection
- 🧩 **Feature Expansion** to include customer demographics, browsing logs, and interaction metadata
