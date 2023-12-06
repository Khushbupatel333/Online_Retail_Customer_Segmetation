# Online_Retail_Customer_Segmetation
# Probelm Statement:-
In this project ,your task is to identify major customers  segmentation on a transitional dataset.The compony mainly sells unique all occasions gifts.Many customers of compony are wholesaler
# variables Discription:-
- Invoice_no : Number of product(Nominal)

- StockCode : Product code(item) (nominal)

- Description : Product Name(Nominal)

- Quantity : The quantity of each product(Numeric)

- InvoiceDate : Date of Invoice (Numeric)

- UnitPrice : Unit Price (Numeric)

- CustomerID : Customer Number (Nominal)

- Country : Country Name (Nominal)
  # Approach :-
  # Data prepration:-
  - Checked for  null values using isnull() method and handled those values.
 
  - Checked the duplicate values from the dataset and remove them.
 
  - Checked out the shape of data ,columns in data ,unique values and basic information.
 
   # Feature Engineering:-
  - Converted Invoive_no column in the string type and dropped all the Invoice_no starting with 'C'.
 
  - Created new features month and Day from InvoiveDate feature.
 
  - Created TotalAmount feature from features Quantity and UnitPrice.
 
  # Models Used:-
  - K-Means
 
  - Silhouette Score Method
 
  - Elbow Method
 
  - DBSCAN Method
 
  - Hierarchical Clustering
 
  # Conclusion:-
  - The main objective of the project is to devlope customer segments for the online store.
 
  - By applying diffrent clusters algorithms I get optimal number fro cluster 2.
 
  - Using the Recency,Frequency and Monetary analysis the customer are segmented into various clusters and I got silhouette score 0.55 for two clusters.





 
