Weekend Movie Trip

Data Source: https://grouplens.org/datasets/movielens/ small data set

The data are contained in the files movies.csv, ratings.csv and tags.csv.

This notebook is a movie recommendation model using K-means clustering and DBSCAN. The two features extracted from the dataset include: Rating and Tags.


Things which I have Done::::

1. Cleaning Data
2. Merging Datasets
3. Rating each Movie
4. No of Tags in each movie
5. Clustering using Kmeans
   --- Calculating the best k value using elbow method
   
   Results:
     There are some overlaping movies for each cluster like Toy story 2 which is cluster 1 and 5. This is beacuse of the            cluster overlap for some particular movies which we can see from our plot.
     
 6.Clustering using DBSCAN
     Results: 
      Even in DBSCAN there is an overlapping of clusters
