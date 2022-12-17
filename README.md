

you can access the python notebook using this link

https://github.com/Chandanraxit07/NETFLIX_MOVIES_TV_SHOWS_CLUSTERING/blob/main/Copy_of_NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING.ipynb



# NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING
![image](https://user-images.githubusercontent.com/98047808/164591625-2544cb28-a8a0-4b6d-9471-3900730f9709.png)


This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

 In this project, you are required to do
 
Exploratory Data Analysis

Understanding what type content is available in different countries

Is Netflix has increasingly focusing on TV rather than movies in recent years.

Clustering similar content by matching text-based features x


# Conclusion

Data set contains 7787 rows and 12 columns in that cast and director features contains large number of missing values so we can drop it and we have 10 features for the further implementation

• We have two types of content TV shows and Movies (30.86%  contains TV shows and 69.14% contains Movies)

• By analysing the content added over years we get to know that in recent years netflix is focusing movies than TV shows (movies is 
increased by 80% and TV shows is increased by 73% compare to 2016 data)

• The most number of the movies and TV shows release in 2017 and 2020 respectively and united nation have the maximum content on netflix

On Netflix, Dramas genre contains the maximum content among all of the genres and the most of the content added in december month and less content in February.

• By applying the silhouette score method for n range clusters on dataset we got best score which is 0.348 for 3 clusters it means content explained well on their own clusters, by using elbow method after k = 3 curve gets linear it means k = 3 will be the best cluster.

• Applied different clustering models Kmeans, hierarchical,Agglomerative clustering on data we got the best cluster arrangments.

• By applying different clustering algorithms to our dataset ,we getthe optimal number of cluster is equal to 3
