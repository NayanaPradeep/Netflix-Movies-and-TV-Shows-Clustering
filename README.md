# Netflix-Movies-and-TV-Shows-Clustering

# Introduction

Netflix, Inc. is an American over-the-top media service and original programming production company. It offers subscription-based video on demand from a library of films and television series, 40% of which is Netflix original programming produced in-house. Netflix has also played a prominent role in independent film distribution.

# PROBLEM STATEMENT

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

1.Exploratory Data Analysis

2.Understanding what type content is available in different countries

3.Is Netflix has increasingly focusing on TV rather than movies in recent years.

4.Clustering similar content by matching text-based features

# Conclusion


*   Netflix has more movies than TV Shows

*   United States provides the most number of movies and shows followed by India and United Kingdom.

*  TV-MA rated content is maximum in number in the dataset. This rating indicates that the content is for mature and adult audience above the age of 17.

*   There is an exponential raise in the number of TV shows and movies distributed by Netflix in the recent years.

*   Text cleaning and vectorization was done on the combined features of the dataset which includes origin country, leading cast member, rating type, content type and description for clustering analysis.

*   Optimal number of clusters were found out to be 25 with silhouette coefficient value of 0.0279

*   Principal component analysis was performed inorder to reduce the higher dimensionality which improved the silhouette coefficient to 0.35. Even though there's improvement in the silhouette score, these cannot be compared as these are two different method of preprocessing is involved.

*   Clusters are identified for each of the record in the dataset.

*   Recommendation based on cosine similiarity is also done on the same transformed data. 
