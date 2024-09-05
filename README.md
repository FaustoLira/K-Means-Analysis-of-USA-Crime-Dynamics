# USA Crime Dynamics

## Introduction

The purpose of this study is to apply K-Means clustering to classify regions of the United States based on levels of violent crime, 
including murder, assault, and rape. By applying this technique to crime data, we aim to identify distinct groups of states with 
similar crime intensity.

Although each type of crime impacts society differently, for the educational purpose of this project, we will determine the level 
of violence based on the average across the different types of crime.

The [USArrests](https://www.rdocumentation.org/packages/datasets/versions/3.6.2/topics/USArrests) is a data set included in *datasets* package in R. It provides, for each of the 50 US states, statistics about assault, murder, rape in arrests per 100,000 residents, and the percentage of the population living in urban areas in 1973.

As a result, a clusterization was obtained, dividing the US territory into 4 clusters:

- Cluster 1 is considered to be moderately high criminality.  
- Cluster 2 is considered to be very high criminality.  
- Cluster 3 can be considered moderately low criminality.
- The Cluster 4 can be considered very low criminality.

The R code was developed through kmeans_USArrests.md file.

## Technical Details

- **Data Preparation**:
  - Cleaning steps were performed, such as checking for null values and duplicates.
  - Performed univariate and bivariate analysis, looking for patterns and anomalies.
  - Applied data scaling, setting the mean as 0 and standard variance as 1 to facilitate comparison between variables.

- **Clustering Method**:
  - K-Means clustering was intended to distinguish regions regarding criminality intensity.
  - The optimal number of clusters was determined using the Elbow and Silhouette methods.
  - K-Means clustering was performed for k values from 2 to 6, with k=4 providing the most distinct and interpretable clustering.
  - Detailed descriptions of each cluster’s characteristics are provided, including average crime rates and urban population percentages.

- **Visualization**:
  - Histograms and scatter plots were used for univariate and bivariate analysis.
  - The correlation heatmap visualized the strength and direction of relationships between different types of crime.
  - PCA plots with two components were used to visualize and interpret the clustering results.

- **Code and Results**:
  - The R Markdown file contains code for data loading, preprocessing, analysis, and visualization.

The markdown file can be visualized through kmeans_USArrests.md file.
