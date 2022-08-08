# Customer_segmenatation
Developed an interactive dash-board for historic sales data of B2C (business-to-consumer) sales. Implemented unsupervised model for Profiling of Customers using python and built report on the clusters obtained in Power Bi. Analyzed, Explored, Performed statistical methods on features and combined multiple table. Imputation of missing values were performed. Tried to implement Dimension Reduction Techniques and retained 80% of variance explained by the model. Normalized the features within a particular range. Built a model using K-mean clustering with k=10 and the optimal value of K=7 is obtained and visualized using KElbowVisualizer. Quality check of the estimated with Silhouette score = 0.196.

Cluster_0 
- This cluster belongs to the customers whose occupation are **Clerical**. 
 The products category on which these customers interests are Clothing and Accessories.
 Customers whose recency is less are having more frequency.

Cluster_1
- These customers are those customers who are more interested into **Bikes**. The frequency of these customers are less might because as they are totally into spending on bikes, basically people don’t buy bikes too often than that of accessories and clothing. 

Cluster_2
- This cluster is a generalized cluster where there is no bias towards any particular occupation.
The product category on which these customers where interested are Bikes. 72% of customers who spent on bikes falls into this cluster.
For the past 6 months the purchase frequency of these customers are increasing.
Most of the Customers under these category are high spending.

Cluster_3
- This cluster belongs to the customers whose occupation are **Professionals**.
The product category on which these customers mostly spent is Clothing. As most of their spending is on clothing the customer recency is low and frequency is high.

Cluster_4
- This cluster belongs to the customers whose occupation are **Management**.
The products category on which these customers where interested in are Accessories and Clothing.
Amount they invested on sales is below 5000. As they are investing on both Clothes and Accessories, Frequency of these customers is more. 

Cluster_5
- This cluster belongs to the customers whose occupation are **Manual** and also low earning customers. 
Frequency of these customers is less but the purchase amount is high. These customers are one time buyers.
The product category on which these customers mostly spent is Accessories.

Cluster_6 
- This cluster belongs to the customers whose occupation are **Skilled Manual**.
The Product category on which these customers mostly spent are Clothing.

Overall from the given data we can see one thing in common for the past 6 months there was a huge increase in the sales.
