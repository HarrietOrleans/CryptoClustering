# CryptoClustering
Module 19 Challenge

CryptoCurrency Clustering with K-Means
This module uses Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

The following libraries and dependencies were provided.
pandas
hvplot
scikit-learn


- I first used StandardScaler to scale he data and created a  DataFrame with coin_id as the index.
- I looped through k values to calculate inertia and then plotted the data an elbow curve. The best value for K was 4.
- Then I created a K-Means model with the scaled data, added predictions to a copy of the DataFrame, and created clusters using hvplot.scatter.
- I used  Principal Component Analysis(PCA)to calculate the variance with explained_variance_ratio_, then store the results in a new PCA DataFrame.
- Created a loop and repeated elbow method for the PCA data. The result I got was that the best value for K was also 4.
- Clustered PCA data with K-Means and visualize.
- After comparing the final composite scatter plot, I think that the PCA data was more clearly defined.
