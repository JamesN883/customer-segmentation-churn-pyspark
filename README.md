# Enhanced Strategic Decision-Making through Customer Segmentation and Customer Churn Prediction with PySpark

## Overview
A practical implementation of PySpark.
This project explores the deployment in handling large-scale analytical workflows and incorporates machine learning models for actionable insights.
Analytics demonstrated through a customer segmentation and churn prediction study case.

## Data
Source:
- Online Retail (Chen, 2015) from UC Irvine Machine Learning Repository.

Description:
- This dataset tracks all transactions made between December 1st, 2010, and December 9th, 2011, for a UK-based online retailer specializing in unique, all-occasion gifts. The company primarily caters to wholesale customers.
- Instances: 541909
- Variables: 8

## Approach
- RFM analysis
- Customer segmentation: K-means clustering
- Churn prediction: random forest and gradient-boosting trees

## Remark and Future Work
The RFM metric is a widely recognized marketing approach for customer segmentation, offering significant benefits when applied alongside k-means clustering.
By integrating PySpark, the handling of large-scale data has been streamlined, leveraging fault tolerance and parallel computation to enhance efficiency.

However, certain challenges were encountered.
Specifically, the training of Random Forest and Gradient Boosting Tree models proved time-intensive, taking approximately four working hours.
To mitigate this limitation, future work could involve deploying HDFS to enable distributed storage and computation.
By utilizing multiple nodes in a cluster, this approach can significantly reduce processing times and optimize resource utilization.
