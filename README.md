# K-Means Clustering for UrbanGB Accident Data

## Overview
This project applies the unsupervised learning technique K-Means Clustering to analyze urban road accident patterns across Great Britain. Using the UrbanGB dataset from the UCI Machine Learning Repository, we implemented a K-Means clustering model to identify spatial clusters of road accidents based on latitude and longitude data. The code can be used to explore underlying urban clusters and provide meaningful insights into urban infrastructure and road safety.

## Dataset
- **Source**: [UC Irvine Machine Learning Repository – UrbanGB Accidents](https://archive.ics.uci.edu/dataset/550/urbangb+urban+road+accidents+coordinates+labelled+by+the+urban+center)  
- **Data Points**: 360,177  
- **Features**: `Longitude` and `Latitude`
- **No missing values** and data was clean

## Objective
Cluster spatial data to uncover patterns in urban accident locations and visualize centroids of densely impacted regions. This helps in identifying areas where policy intervention, traffic regulation, or urban redesign may be necessary.

## Methodology
- Imported and visualized coordinate data in Python
- Scaled longitude for appropriate geospatial representation (longitude scaled by 1.7)
- Applied K-Means clustering using the scikit-learn library
- Determined optimal number of clusters using the elbow method
- Visualized clustering results with an interactive HTML map

## Results
Clusters formed through K-Means aligned with the geographic distributions of GB cities. The visualization clearly depicts accident hotspots and revealed insights into urban sprawl and traffic density.

## Viewing the Map
Execute the code. Then, check the directory/folder the file is in and click on the HTML file that should be there to view the map.
