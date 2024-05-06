# CryptoClustering

# Introduction
In this project, Python and unsupervised learning techniques are employed to predict whether cryptocurrencies are affected by 24-hour or 7-day price changes. The goal is to utilize K-means clustering and Principal Component Analysis (PCA) to analyze and cluster cryptocurrency data.

# Instructions
# 1. Prepare the Data
- Load the crypto_market_data.csv into a DataFrame.
- Get summary statistics and plot the data to understand its structure.

# 2. Normalize Data
- Use StandardScaler() from scikit-learn to normalize the data.
- Create a DataFrame with the scaled data and set the "coin_id" index.

# 3. Find the Best Value for k Using the Original Scaled DataFrame
- Employ the elbow method to find the best value for k.
- Plot a line chart to identify the optimal value for k.

# 4. Cluster Cryptocurrencies with K-means Using the Original Scaled Data
- Initialize the K-means model with the best value for k.
- Fit the model using the original scaled DataFrame.
- Predict the clusters and create a scatter plot using hvPlot.

# 5. Optimize Clusters with Principal Component Analysis (PCA)
- Perform PCA and reduce features to three principal components.
- Retrieve the explained variance and create a new DataFrame with the PCA data.

# 6. Find the Best Value for k Using the PCA Data
- Use the elbow method on the PCA data to find the best value for k.
- Plot a line chart to visually identify the optimal value for k.

# 7. Cluster Cryptocurrencies with K-means Using the PCA Data
- Initialize the K-means model with the best value for k.
- Fit the model using the PCA data.
- Predict the clusters and create a scatter plot using hvPlot.

# 8. Answer the Question:
What is the impact of using fewer features to cluster the data using K-Means?
