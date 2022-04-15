# Netflix-Movies-and-Tv-shows-clustering

#This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.


#Attribute Information
show_id : Unique ID for every Movie / Tv Show

type : Identifier - A Movie or TV Show

title : Title of the Movie / Tv Show

director : Director of the Movie

cast : Actors involved in the movie / show

country : Country where the movie / show was produced

date_added : Date it was added on Netflix

release_year : Actual Releaseyear of the movie / show

rating : TV Rating of the movie / show

duration : Total Duration - in minutes or number of seasons

listed_in : Genere

description: The Summary description

1. Import Libraries
2. Import Data
3. Elementary Analysis
4. Data Cleaning and data Visualization
5. Generate Word embeddings
6. Define Model and create clusters
   6.1 DBSCAN
   6.2 Mean Shift
   6.3 Agglomerative clustering
   6.4 KMeans
   6.5 BIRCH
   6.6 Gaussian Mixture
   6.7 OPTICS
   6.8 MiniBatch KMeans
# **7. Conclusion**
From the diffrent clutering algorithms we trained our data on, DBSCAN and Mean Shift seems to be not able to properly cluster the data. Agglomorative Clustering, BIRCH, KMeans and Gaussian mixture does a good job on identifying the clusters. Also we can observe from the cluster data that these models have been able to identify the proper segment types in the data. So these models can be used for future work to further tune and produce better results.
