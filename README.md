#  Customer Segmentation Analysis : Machine Learning 
![Cust](https://github.com/user-attachments/assets/a0efb521-0904-410f-a73c-174913d3c4c3)

# Problem Statement:-
In this project, your task is to identify major customer segmentation on a transitional dataset. The company mainly sells unique occasions gifts. Many customers of the company are wholesalers
# variables Discription:-
- Invoice_no : Number of product(Nominal)

- StockCode : Product code(item) (nominal)

- Description: Product Name(Nominal)

- Quantity: The quantity of each product(Numeric)

- InvoiceDate: Date of Invoice (Numeric)

- UnitPrice: Unit Price (Numeric)

- CustomerID: Customer Number (Nominal)

- Country: Country Name (Nominal)
  # Approach:-
  # Data preparation:-
  - Checked for null values using the isnull() method and handled those values.
 
  - Checked the duplicate values from the dataset and removed them.
 
  - Checked out the shape of data, columns in data, unique values, and basic information.
 
   # Feature Engineering:-
  - Converted the Invoice_no column in the string type and dropped all the Invoice_no starting with 'C'.
 
  - Created new features month and Day from the InvoiceDate feature.
 
  - Created TotalAmount feature from features Quantity and UnitPrice.
 
  # Models Used:-
  - K-Means
 
  - Silhouette Score Method
 
  - Elbow Method
 
  - DBSCAN Method
 
  - Hierarchical Clustering
 
  # Conclusion:-
  - The main objective of the project is to develop customer segments for the online store.
 
  - By applying different cluster algorithms I get the optimal number for cluster 2.
 
  - Using the Recency, Frequency, and Monetary analysis the customers are segmented into various clusters and I got a silhouette score of 0.49 for two clusters.




 
