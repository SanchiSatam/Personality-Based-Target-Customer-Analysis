# Object
The primary objective of this project is to delve into the sophisticated space of client personalities and preferences. Recognizing the paramount significance of understanding individual consumer traits, the project aims to employ advanced data mining techniques and Python programming to extract meaningful insights. 
By focusing on the detailed analysis of client personalities, the project works to unravel patterns and behaviors that inform the creation of tailored marketing strategies.

# Model Development:
K-Mean Clustering algorithm:
To segment the data into distinct groups or clusters, we have performed K-Means clustering by choosing an optimal value of k, which is the no of cluster determined by the elbow method.

# Results
The results provide the centroid values of each cluster after K-Meas algorithm is applied to the dataset. The three clusters created are Cluster 0, Cluster 1 and Cluster 2.

Income:
Cluster 0 has average income of about $ 37816.80  and Cluster 1 has the highest income of about $73960.50 whereas income of Cluster 2 falls in the average range of around $67717.77.

Recency:
Recency of the three created clusters is as follows:
Cluster 0: Average recency of 48.44 days
Cluster 1: Average recency of 50.45 days
Cluster 2: Average recency of 49.38 days

Marital_Married:
The binary value (0,1) represents the marital status “Married”
Cluster 0: 39.28 % married customers
Cluster 1: 36.50 % married customers
Cluster 2: 38.78 % married customers

MntTotal:
This represents the amount spent on products.
Cluster 0: Average spending of $147.93
Cluster 1: Average spending of $1452.44
Cluster 2: Average spending of $915.87

Childrenhome:
The binary value (0,1) represents if there are children present at home
Cluster 0: 86.53% have children at home
Cluster 1: 42.33 % have children at home
Cluster 2: 56.57 % have children at home

Is_Educated:
The binary value (0,1) represents if there are customers having degrees beyond bachelors
Cluster 0: 35.46 % are educated individuals
Cluster 1: 54.91 % are educated individuals
Cluster 2: 34.62 % are educated individuals

These insights provide us the characteristics of each cluster and helps us to understand the behaviors and features of the customers falling inside each cluster.
# Business Insights
Insights on Cluster 0 customers:
These customers have Medium Income, moderate no. of children and spend moderate amount of money to buy products especially wines. This group could be targeted by the marketing team with a mix of premium and budget-friendly products. This group might be interested in children products as well as adult products since the no. of children is moderate.

Insight on Cluster 1 customers:
These customers have low income but more no. of children and they spend less amount of money buying any products. Since the no. of children of these customers are more, they can be targeted by the marketing team with products healthier for the kids and products that are budget-friendly, on sale, having great offers etc. They might be more interested in products for kids or teenagers.

Insight on Cluster 2 customers:
These group of customers are people who have high income and they spend the most, especially on wine. The no. of children in this cluster is the lowest. Therefore, this group of customers can be targeted with premium products and promotions related to wine. This group will have disposable income since they have fewer children.
