# CryptoClustering

Overview
The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques, specifically K-means clustering. Additionally, the project explores the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering.

Steps
Load and preprocess the data.
Scale the data using StandardScaler.
Find the best value for k using the elbow method.
Cluster cryptocurrencies with K-means using the original scaled data.
Perform PCA to reduce the features to three principal components.
Find the best value for k using the PCA data.
Cluster cryptocurrencies with K-means using the PCA data.
Visualize and compare the results using hvPlot.
Results
The project includes the following visualizations:

Elbow curve for the original data.
![elbow_curve](https://github.com/deepikarapeti43/CryptoClustering/assets/127686390/8c24eac7-1ff7-4a1b-84e4-bcefd1330c97)


Elbow curve for the PCA data.
![elbow_curve](https://github.com/deepikarapeti43/CryptoClustering/assets/127686390/aac2d2e1-e020-47ed-9b39-4406da892f61)


Scatter plot of cryptocurrency clusters based on the original data.
![market_scaled_plot](https://github.com/deepikarapeti43/CryptoClustering/assets/127686390/12eed550-60cc-4b66-8935-5d2f16105d50)

Scatter plot of cryptocurrency clusters based on the PCA data.
![scatter_pca](https://github.com/deepikarapeti43/CryptoClustering/assets/127686390/ebc769c3-27c3-45fe-b9af-3aedd831e3f7)


Conclusion
The project analyzes the impact of using fewer features on clustering the data using K-means. Comparing the clustering results of the original data and the PCA data helps to understand the effect of dimensionality reduction on the clustering process.

Dependencies
Python
pandas
NumPy
scikit-learn
hvPlot
