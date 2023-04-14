# analysis

Test cluster analysis code using sklearn datasets using the following steps:

- Create a Simulated Data for Illustration
  - plot sctter plots using sample data of 300 records using make_blobs
  
- Clustering
  - define fit and predict clusters using DBSCAN Kmeans and Agglomerative Clustering
  - compare clusters
  
- TfidfVectorizer
  apply TfidfVectorizer to associate each word with a number that represents how relevant each word is in the data
  
- Apply Levenshtein Distance with KMedoids Model
  - use Levenshtein Distance to evaluate the difference between records by calulating the insertions, deletions or substitutions 
    that differenciates one recored from the other
    
- Plot a Dendrogram for Agglomerative Clustering
  - use the prefered cluster (Agglomerative Clustering) to plot a dendogram to visislly show the relationship between records
  - agglomerative Clustering was used because the distance between each cluster was the most defined therefore showing the most unique set of clusters
