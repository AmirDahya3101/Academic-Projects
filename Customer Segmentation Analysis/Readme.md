# Customer Segmentation Analysis Project 🎯🔍
This project aims to perform customer segmentation analysis using RFM (Recency, Frequency, Monetary) analysis and K-means clustering. The dataset used contains information about customers' purchase behavior. 📊🛍️

## Purpose
The purpose of this project is to segment customers into different groups based on their buying patterns and identify valuable customer segments. By analyzing customers' recency, frequency, and monetary values, we can gain insights into their behavior and tailor marketing strategies accordingly. 🎯📈

## Steps Involved
* Data Preprocessing: Load the RFM data and perform data cleaning by removing outliers using z-scores. 🧹📊
* Outlier Analysis: Create box plots to check for outliers in the original data and compare them with the cleaned data. 📉🔍
* Histogram Analysis: Generate histograms for the cleaned data to visualize the distribution of recency, frequency, and monetary values and compare them with the original histograms. 📊📈
* K-means Clustering: Perform cluster analysis using K-means clustering with the original RFM dataframe to segment customers. 📊🔢
* Graph Visualization: Plot graphs to visualize the clusters based on frequency vs. monetary, recency vs. monetary, and recency vs. frequency. 📈🔍
* Elbow Method: Determine the optimal number of clusters using the elbow method and perform cluster analysis with k=4. ⚙️📊
* Visualization with Cleaned Data: Repeat the cluster analysis with the cleaned data and visualize the clusters. 📊🧹

## Results
The analysis provides insights into customer segmentation based on their buying behavior. By analyzing the graphs and clusters, we can make the following observations: 📈🔍🔢

* Cluster Analysis with Original Data:
  * Frequency vs. Monetary: Customers in Cluster 1 tend to have higher frequency and lower monetary values, while customers in Cluster 2 have lower frequency and higher monetary values. Cluster 0 represents customers with lower frequency and monetary values.
Recency vs. Monetary: Cluster 1 consists of customers with higher recency and monetary values, while Cluster 2 has lower recency and higher monetary values. Cluster 0 represents customers with lower recency and monetary values.
Recency vs. Frequency: Cluster 1 includes customers with higher recency and frequency values, while Cluster 2 has lower recency and higher frequency values. Cluster 0 represents customers with lower recency and frequency values.
Cluster Analysis with k=4:

  * Frequency vs. Monetary: Customers in Cluster 1 have higher frequency and lower monetary values, while customers in Cluster 2 have higher frequency and higher monetary values. Cluster 0 represents customers with lower frequency and monetary values, and Cluster 3 consists of customers with higher frequency and significantly higher monetary values.
Recency vs. Monetary: Cluster 1 represents customers with higher recency and monetary values, Cluster 2 has lower recency and higher monetary values, and Cluster 3 represents customers with higher recency and significantly higher monetary values. Cluster 0 consists of customers with lower recency and monetary values.
Recency vs. Frequency: Cluster 1 includes customers with higher recency and frequency values, Cluster 2 has lower recency and higher frequency values, and Cluster 3 represents customers with higher recency and frequency values.


Contact Information 📞✉️
If you have any questions or need further assistance, please feel free to contact me at ad180@myscc.ca I would be happy to help!

Happy analyzing! 🚀🔍
