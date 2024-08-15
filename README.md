# K-Means Analysis of USA Crime Dynamics

## Introduction

The purpose of this study is to apply K-Means clustering to classify regions of the United States based on levels of violent crime, including murder, assault, and rape. By applying this technique to crime data, we aim to identify distinct groups of states with similar crime intensity.

Although each type of crime impacts society differently, for the educational purpose of this project, we will determine the level of violence based on the average across the different types of crime.

The [USArrests](https://www.rdocumentation.org/packages/datasets/versions/3.6.2/topics/USArrests) is a data set included in *datasets* package in R. It provides, for each of the 50 US states, statistics about assault, murder, rape in arrests per 100,000 residents, and the percentage of the population living in urban areas in 1973.

As a result, a clusterization was obtained dividing the US territory into 4 clusters:

- The Cluster 1 has a considered moderately high criminality.  
- The Cluster 2 has a considered very high criminality.  
- The Cluster 3 can be considered moderately low criminality.
- The Cluster 4 can be considered very low criminality.

The R code can be viewed through the file kmeans_USArrests.md.
