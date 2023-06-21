# Unsupervised_Machine_Learing_Netflix_project
**Problem Statement**
To cluster the given movies and Tv shows using the unsupervised machine learning algorithms and then create a recommendation system based on that clustering.
**Data Description**
The original dataframe had 11 columns
show_id : id of the show
type : type as movie or Tv show
title : name of the movie or show
director : name of the director
cast : names of the actors involved
country : country in which it was released
date_added : added date on the portal
release_year : release year
rating : rating based on for adults, infants, children etc.
duration : length of movie or tv show
listed_in : genre in which it is listed
description : basic outline of the movie or tv show

Later more columns were added like nlp, no_stp_words and no_puntuation for applying the algorithms efficiently.

**Approach**
Removing null Values
EDA
Stemming
Vectorization
Principal Component Analysis for decomposition
Clustering
Designing Recommmendation system
**Models Used**
1.kmeans Clustering using Elbow method
2.kmeans Clustering using Silhouette Analysis
3. Gaussain Mixture model
4. Hierarchial Clustering
**Conclusion**
1.From EDA it was found that Highest number of titles were relaesed in USA followed by India and UK.

2. In 2017 highest number of movies were released while in 2020 highest number of Tv shows were relaesed.

3. In USA highest number of directors focus on Adult category while in India the highest number of title focus on children. Thus giving picture of the demography of the countries.

4. After Analysing the Elbow method, Silhouette Analysis, Dendogram and plot of Aic and Bic values the optimal clusters were chossen to be 8.

5. At last the recommendation system was made using k means clustering giving 10 recommendations.
   

