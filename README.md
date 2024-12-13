# Florida-biodiversity-spot-exploration
This website aims to help people in Florida explore the nearby biodiversity hotspots.

Florida Biodiversity Cluster Map
Overview
This interactive map visualizes biodiversity clusters in Florida using iNaturalist research-grade data from GBIF (Global Biodiversity Information Facility). The map allows users to explore biodiversity hotspots and their properties based on zip codes.

Features
Interactive map of Florida showing biodiversity clusters
Cluster analysis based on DBSCAN algorithm (10 points within 1 km)
Cluster property identification including user diversity and main species
Zip code-based cluster lookup
Aerial map view option
Display of top species in each cluster
Data Source
GBIF (Global Biodiversity Information Facility)
Dataset: iNaturalist research-grade observations in Florida from 2021 to 2024
Methodology
Data acquisition: Downloaded Florida iNaturalist research-grade data from GBIF
Cluster analysis: Implemented DBSCAN algorithm to identify clusters (10 points within 1 km)
Cluster property analysis: Determined user diversity and main species for each cluster
Map creation: Utilized geopy and Leaflet to generate an interactive map
Functionality implementation: Developed features for zip code-based searches, aerial view toggling, and top species display
How to Use
Enter a zip code to view biodiversity clusters in that area
Click on clusters to view detailed properties
Toggle between standard and aerial map views
Explore top species in each cluster
Technologies Used
Python (data processing and analysis)
DBSCAN algorithm (clustering)
geopy (geocoding and distance calculations)
Leaflet (interactive mapping)
Future Improvements
Add time-based filtering of observations
Implement species-specific searches
Expand the dataset to cover a larger geographical area
Contributors
Jiping
