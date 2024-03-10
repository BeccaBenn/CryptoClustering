Project: Cryptocurrency Clustering
Overview
This project was completed for UCSB Data Analytics Bootcamp. It focuses on clustering cryptocurrencies based on their market
performance using K-means clustering and Principal Component Analysis (PCA). The analysis aims to identify groups of
cryptocurrencies with similar market trends and behaviors.

Data Preparation
Normalization:
Normalize the data using StandardScaler() from scikit-learn.
Create a new DataFrame with the scaled data, setting the "coin_id" index from the original DataFrame.

Finding the Best Value for K Using Original Scaled Data
Elbow Method:
Implement the elbow method to find the optimal value for k.
Generate a line chart displaying the inertia values for different values of k.

Clustering Cryptocurrencies with K-means Using Original Scaled Data
K-means Clustering:
Initialize the K-means model with the best value for k.
Fit the K-means model using the original scaled DataFrame.
Predict clusters to group cryptocurrencies.
Visualize the clustered cryptocurrencies using scatter plots.

Optimizing Clusters with Principal Component Analysis (PCA)
Principal Component Analysis:
Conduct PCA to reduce feature dimensions to three principal components.
Determine the total explained variance of the three principal components.
Create a new DataFrame with the PCA data.

Finding the Best Value for K Using PCA Data
Elbow Method with PCA:
Apply the elbow method to find the optimal value for k using PCA data.
Plot a line chart displaying inertia values for different k values.

Clustering Cryptocurrencies with K-means Using PCA Data
K-means Clustering with PCA:
Initialize the K-means model with the optimal value for k derived from PCA.
Fit the K-means model using the PCA-transformed data.
Predict clusters to group cryptocurrencies.
Visualize the clustered cryptocurrencies using scatter plots.
