![Credit-card-fraud-top](https://github.com/user-attachments/assets/a07c0e9e-c94f-41f0-a39a-40e6ac5e0a53)



# Anomaly-detection---Credit-Card
identify fraud transaction 
- this assignment, you will use anomaly detection techniques to detect credit card fraud using this modified dataset originally from Kaggle.
 - Each row represents one credit card transaction.
- This dataset has anonymized features, except for the amount of the transaction.
- Your stakeholder reports that they have found that about 0.4% of transactions are fraudulent, and 99.6% are valid.
- Your task will be to locate anomalous transactions in this data using KMeans and Isolation Forest models
#KMeans:
- Remember to scale your data.
- Fit a KMeans model to create 3 clusters. Please use a random state of 42 for your model.
- Use scipy.spatial.distance.cdist to create a matrix of distances between each - data point and each cluster center
- Define a list of the indices of the anomalous data using the threshold given by the stakeholder (99.6% valid).
- Note that you cannot visualize your clusters since this dataset has 29 features. (To visualize, you could apply PCA to reduce the dimensionality to 2 features, but visualization is not required.)
