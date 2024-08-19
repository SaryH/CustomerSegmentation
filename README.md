# CustomerSegmentation
 Demographic segmentation using K-Means clustering to identify key customer segments and compare them. My graduation project for the Introduction to Machine Learning with TensorFlow Nanodegree.

This project focuses on segmenting the general population of Germany and mapping customer data for a mail-order sales company onto these demographic clusters. The goal is to identify key customer segments and understand how they compare to the broader population.

Project Overview
Data Source: The project uses demographic data from Germany and customer data from a mail-order company.
Objective: To segment the general population into distinct clusters and analyze how the company's customer base maps onto these clusters.
Tools Used: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Key Steps
Data Preprocessing:

Handled missing data by assessing rows with excessive missing values.
Re-encoded categorical features using one-hot encoding.
Engineered mixed-type features to make them suitable for clustering.
Feature Scaling:

Applied standardization to ensure all features contributed equally to the clustering process.
Dimensionality Reduction:

Performed PCA to reduce the dimensionality of the dataset while retaining 90% of the variance.
Selected 34 principal components for the clustering analysis.
K-Means Clustering:

Applied K-Means clustering to the PCA-transformed general population data.
Chose 30 clusters based on the "elbow method," although the elbow was not very distinct.
Visualized the clusters in 2D space using the first two principal components.
Customer Data Mapping:

Applied the preprocessing and transformation steps to the customer data.
Mapped customer data onto the clusters identified from the general population.
Cluster Analysis:

Compared the proportion of customers in each cluster to the general population.
Identified overrepresented and underrepresented clusters, providing insights into the company's target demographics.
Results
The analysis revealed distinct demographic clusters within the general population, some of which are more likely to be customers of the mail-order company.
Overrepresented clusters in the customer data were identified, suggesting key target audiences for the company’s products.
Underrepresented clusters highlighted potential areas for market expansion.
Conclusion
This project demonstrates the application of K-Means clustering to demographic data for market segmentation. By understanding the demographic profiles of their customers, the company can better tailor their marketing strategies to specific segments of the population.