This project is part of our final year submission for the Bachelor of Engineering (Computer Engineering). 
# Team Members
1)Jayesh Wagh, 
2)Bhupesh Bhadane, 
3)Nandini Ahire

# Customer-Segmentation-with-RFM-Analysis
This project is created to segment customer based on their buying pattern using RFM Analysis. Further creating K-Mean Clustering model for more precise segmentation for optimize result
Dataset Link: https://www.kaggle.com/datasets/tunguz/online-retail

# Description 
This project is constructed to segment customers based on their buying patters.

* Conduct RFM Analysis to divide customers on differnt groups.
* Produce K-means clustering unsupervised machine learning model to form clusters of customer with similar recency, frequency, monetary
* Observe each clusters and then make conclusion
## RFM Analysis
RFM Analysis is a concept used by Data Science professionals, especially in the marketing domain for understanding and segmenting customers based on their buying behaviour.
Using RFM Analysis, a business can assess customers’:
* Recency (the date they made their last purchase)
* Frequency (how often they make purchases)
* Monetary (the amount spent on purchases)
Recency, Frequency, and Monetary value of a customer are three key metrics that provide information about customer engagement, loyalty, and value to a business.
## K-Mean Clustering
Based on Recency, Frequency, Monetary K-mean clustering model is created.Before model the data is preprocessed using log transformation, scaling and outliers treatment using Windsorization. Using Flatten Clustering Plot and silhouette score, 4 cluster for optimized clustering is concluded
## K-Mean Clustering Interpretation
  Here are the interpretation of each cluster
* Cluster0: Most Recent customer with average frequency and monetary, mostly "Look out buyers".
* Cluster1: "Best Customers" with recent puchases, most frequent buyers with higher monetary investment
* Cluster2: "Lost Cheap Customer" with last purchase long ago, purchased very few times with little spend
* Cluster3: "Almost Lost Customer" , who haven’t purchased for some time(R=3), but used to purchase frequently and spent a lot
