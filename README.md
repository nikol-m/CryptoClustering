# CryptoClustering

In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

The concept of Cryptocurrency Clustering entails a venture with the objective of categorizing distinct cryptocurrencies based on their market data, thereby unearthing underlying patterns and correlations.

Project Overview
This undertaking harnesses a spectrum of data science methodologies and tools, encompassing KMeans clustering, Principal Component Analysis (PCA), and interactive visualization via hvplot. Through the application of clustering to cryptocurrencies, we can attain a heightened comprehension of market dynamics, facilitating more astute investment decisions.

Data Compilation
The dataset employed in this endeavor encompasses a gamut of market metrics for diverse cryptocurrencies, encompassing the percentage adjustments in prices across varying timeframes.

Attributes
- Data Cleansing & Exploration: The task involved the loading and exploration of cryptocurrency market data, accompanied by an initial visualization of data trends.
- Data Preprocessing: To enhance clustering outcomes, the data underwent normalization through scikit-learn's StandardScaler.
- KMeans Clustering: The incorporation of KMeans clustering served to cluster the array of cryptocurrencies.
- Elbow Method: The elbow method was employed to discern the optimal cluster count (k) for the dataset.
- Principal Component Analysis (PCA): Through PCA, data dimensionality was reduced for visualization purposes, while also gauging the impact of dimensionality reduction on 
  clustering outcomes.
- Visual Presentation: Interactive visualizations utilizing hvplot were leveraged to facilitate visual scrutiny of clusters and the elbow curve.

Key Discoveries
Optimal Cluster Count: Both the original dataset and the PCA-reduced data indicate an optimal value of 4 for the parameter k.
PCA Explained Variance: The three principal components utilized in PCA accounted for approximately 89.5% of the cumulative variance.
Cluster Analysis: Based on scatter plots, two clusters stood apart from the remainder, hinting at distinctive attributes of these cryptocurrencies in contrast to the majority.

- Prerequisites
- Python
- Pandas
- Scikit-learn
- hvplot
- matplotlib

Utilization
1. Clone the repository.
2. Confirm the presence of all necessary libraries.
3. Execute the script within your preferred environment.
4. Scrutinize hvplot visualizations to glean insights from the cryptocurrency clustering outcomes.

In Conclusion
The endeavor of Crypto Clustering paves the way for a more profound comprehension of parallels and distinctions amidst assorted cryptocurrencies. Through the amalgamation of dimensionality reduction via PCA and the application of KMeans clustering, we can effectively classify cryptocurrencies, potentially unveiling latent trends in the market.
