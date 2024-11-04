# PRODIGY_ML_Task2

# K-Means Clustering for Customer Segmentation in Retail

This project utilizes K-means clustering to effectively segment customers of a retail store based on their annual income and spending scores, derived from purchase history. The goal is to analyze transaction data to identify distinct customer groups, which can enhance targeted marketing strategies and improve personalized shopping experiences.
## Project Overview

The project begins with the loading of customer transaction data from a CSV file into a Pandas DataFrame. Initial exploratory data analysis (EDA) is performed to understand the dataset's structure, including data types, non-null counts, and any missing values.
## Data Preprocessing

To prepare the data for clustering, the relevant features—annual income and spending score—are extracted from the dataset. This selection is crucial as it directly influences the effectiveness of the clustering algorithm.
## K-Means Implementation

The K-means clustering algorithm is implemented to group the customers into distinct segments. The process involves determining the optimal number of clusters through the elbow method, which analyzes the Within-Cluster Sum of Squares (WCSS) for different cluster counts. This helps identify the point where adding more clusters yields diminishing returns.
## Evaluation of Clusters

After fitting the K-means algorithm with the chosen number of clusters, each customer is assigned a cluster label. The results are visualized through scatter plots, illustrating the customer segments and their respective centroids. This visual representation aids in understanding the characteristics of each group.
## Conclusion

The insights gained from this analysis will enable the retail store to develop targeted marketing strategies and personalized experiences tailored to the unique needs of each customer segment. By leveraging customer data more effectively, the retail store can enhance customer satisfaction and drive sales growth.

## Dataset

The dataset used for this project can be found at the following link:https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
