
Customer Segmentation Using RFM Analysis, K-Means, and Random Forest

Overview
This repository contains the code and resources for a research project focused on customer segmentation using a hybrid approach of RFM Analysis, K-Means Clustering, and Random Forest. The project demonstrates how data-driven segmentation can help businesses better understand customer behavior, enabling personalized marketing strategies and improving customer retention.

Key Features
RFM Analysis: Calculates Recency, Frequency, and Monetary value for each customer to rank their transaction behavior.
K-Means Clustering: Groups customers into distinct segments based on their RFM scores.
Random Forest: Validates the importance of RFM features and assists in predictive customer classification.
Visualization: Includes detailed graphs for cluster analysis, PCA, and customer distribution insights.
Project Motivation
Modern businesses need accurate and actionable customer segmentation to design targeted marketing campaigns. This project bridges the gap between traditional segmentation methods and advanced machine learning techniques for superior accuracy and scalability.

Methodology
Data Preprocessing:
Cleaned and processed raw transactional data.
Handled missing values and outliers.
Feature Engineering:
Calculated RFM scores for each customer.
Clustering:
Applied K-Means to segment customers into clusters based on their RFM scores.
Determined optimal clusters using the Elbow method.
Predictive Analysis:
Used Random Forest to analyze feature importance and classify customer segments.
Visualization:
Created visualizations for better understanding of cluster characteristics and key findings.

Requirements
To run this project, ensure you have the following installed:
Python 3.8+
Required Libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn
