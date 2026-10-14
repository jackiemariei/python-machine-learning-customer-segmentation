# Machine Learning: Customer Segmentation

## Project Overview

This project uses unsupervised machine learning to identify customer segments for a German mail-order company. By comparing demographic data from the general population with the company's existing customers, the analysis identifies population groups that are overrepresented or underrepresented in the customer base.

The goal is to help the company better understand its customers and identify potential audiences for targeted marketing.

## Business Objectives

- Clean and prepare large demographic datasets for analysis.
- Apply feature scaling and Principal Component Analysis (PCA) to reduce dimensionality.
- Use K-means clustering to identify demographic segments.
- Compare customer segments with the general population.
- Translate clustering results into actionable business insights.

## Tools and Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Principal Component Analysis (PCA)
- K-means clustering
- Unsupervised machine learning
- Exploratory data analysis and data preprocessing

## Analysis Process

**1. Data Cleaning and Preparation**

Cleaned demographic datasets by handling missing values, removing irrelevant features, and preparing the data for machine learning. Missing-data patterns were also examined to understand their impact on the analysis.

**2. Feature Scaling and Dimensionality Reduction**

Applied feature scaling and PCA to reduce the dataset from 64 features to 20 principal components while retaining approximately 80% of the variance.

**3. Customer Segmentation**

Evaluated different cluster counts and selected 10 clusters using K-means clustering. The model was fitted to the general population data to establish demographic segments.

**4. Customer Comparison**

Applied the same preprocessing steps, PCA transformation, and clustering model to the company's customer data. Compared the resulting cluster distributions to identify demographic groups that were overrepresented or underrepresented among customers.

## Key Findings

- **Core customer segment:** Cluster 0 represented approximately 7.5% of the general population but 33.5% of the customer base, making it roughly 4.5 times as prevalent among customers.
- **Additional customer segments:** Clusters 6 and 7 were also overrepresented among customers.
- **Underrepresented segments:** Clusters 1, 3, 8, and 9 appeared less frequently in the customer base than in the general population.
- **Data quality:** Missing demographic information affected both datasets, with approximately 10% of the general population and 26% of customers excluded during cleaning because of extensive missing values.

The findings suggest that the company's existing customer base is concentrated in particular demographic segments rather than evenly distributed across the population. These insights can help inform future marketing and customer acquisition strategies.

## Project Files

- `Identify_Customer_Segments.ipynb`: Jupyter Notebook containing the code, analysis, visualizations, and discussion of findings.
- `Identify_Customer_Segments.html`: Browser-friendly version of the completed notebook.

## Skills Demonstrated

Data cleaning, exploratory data analysis, feature engineering, dimensionality reduction, unsupervised machine learning, clustering, data interpretation, and communicating data-driven business insights.
