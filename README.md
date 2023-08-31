# Module-19-CryptoClustering

To begin, I had to scale the data using StandardScaler() to make sure the data was not going to be skewed or weighted unevenly, then I could begin finding the best value for 'k' using the scaled data. I found that k=4 seemed to be a good fit.

Using K-means and PCA on the scaled data, I could then fit and predict a model and plot the predictions into scatter plots. While using the elbow method on the PCA data, I also found that k=4 again seemed to be best and plotted the data using this value.

However, clustering the PCA data using K-means resulted in a different distribution of points on the scatter plot, most likely from the different weight distribution on fewer features of the data.