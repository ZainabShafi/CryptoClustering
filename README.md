# CryptoClustering Analysis 

## OVERVIEW: 

This project performs clustering analyses on cryptocurrency market data using the KMeans model and Principal Component Analysis (PCA). The goal was to group cryptocurrencies based on their price change percentages over time, which enhanced my understanding of clustering techniques.
Learning to apply the Elbow method was particularly valuable, as it provided a critical tool for statistical decision-making. Additionally, gaining insights into data preprocessing, such as scaling, and component reduction through PCA has deepened my data analytics skills, helping me understand the underlying processes when working with data in my professional and academic experiences.

## Professional Use: 

1) Enhanced Decision-Making
2) Risk Assessment
3) Market Segmentation
4) Reporting and Visualization
5) Optimized Strategies

## Technologies Used:

**Python:** The primary programming language for the analysis.

**Pandas:** For data manipulation and analysis, particularly for handling the cryptocurrency dataset.

**Scikit-learn:** For implementing machine learning algorithms, including K-means clustering and PCA.

**HVPlot:** For interactive visualization of data, making it easier to visualize the results of clustering and PCA.

## Analysis Steps: 

**Data Preparation:**

Load the data and display initial statistics.
Scale the data using *StandardScaler* for better clustering results.

**Determine Optimal k:**

Use the *Elbow method* to determine the best value for k (number of clusters) using both the original and PCA-transformed data.

**Clustering:**

Apply *K-means* clustering to group cryptocurrencies into distinct clusters based on their price change percentages.
Visualize the results using scatter plots.

**Principal Component Analysis:**

Reduce the dimensionality of the dataset to three *principal components* and analyze the *explained variance*.

**Final Clustering with PCA:**

Perform K-means clustering again using the PCA data to identify cryptocurrency clusters.

