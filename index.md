# Exploring the Geospatial Dynamics of Third Wave and Local Cafes in New York City
### Author: <a href="mailto:nilayvinchhi@gmail.com">Nilay Vinchhi</a>
## Introduction
The proposed research project aims to provide an in-depth understanding of the clustering patterns of third wave and local cafes in New York City (NYC). Third wave and local cafes have gained popularity in recent years due to their focus on specialty coffee, unique atmosphere, and locally-sourced ingredients. These cafes have played a significant role in driving the growth of the coffee industry in the city. By examining the spatial distribution of these cafes and analyzing the factors contributing to their clustering, this study seeks to shed light on the dynamics of NYC's cafe culture.

## Research Questions
The project will address the following research questions:

1. Where are the clusters of third wave and local cafes located in NYC?
2. Which demographic characteristics of the surrounding neighborhoods influence the clustering of these cafes? Factors such as income, age, gender, and dependency ratio will be considered.
3. How far are individuals willing to travel to access these cafes?
## Data Sources
To investigate these research questions, the project will utilize two primary datasets:

1. OSM POI Data: This dataset provides point data on the locations of cafes in NYC. The dataset was obtained from the OpenStreetMap (OSM) database using the Overpass Turbo API. It should be noted that the OSM dataset may have limitations in terms of completeness and accuracy.

2. Census Tracts Data: This dataset includes demographic information on the surrounding neighborhoods, such as income, age, gender, and dependency ratio. The data will be obtained from the TIGER shapefiles and census demographics data provided by the US Census Bureau.

## Methodology
The project will employ GIS tools and spatial analysis techniques in Python to analyze the datasets. The following methods will be utilized:

1. Spatial Join: To combine the cafe point data with the census tracts data, a spatial join operation will be performed. This operation will merge the attributes of the two datasets based on their spatial relationship.

2. Data Aggregation: The data will be aggregated to a higher level of resolution, such as census tracts or neighborhoods. This will allow for a comprehensive analysis of the demographic characteristics of the areas surrounding the cafes.

3. Chloropleth Maps: Static maps will be generated to visualize the median age of the surrounding neighborhoods and the cafe-to-population ratio. These maps will provide insights into the spatial patterns of cafes and their relationship with demographic variables.

4. Multi-linear Regression: A multi-linear regression analysis will be conducted on the census tracts with the highest cafe-to-population ratio. This analysis will help identify the relationships between demographic variables and the clustering of cafes.

5. Distance Analysis: The project will explore the distance that people are willing to travel to access these cafes. This analysis will provide valuable information for cafe owners, urban planners, and policymakers.

## Limitations and Data Quality
It is important to acknowledge the limitations and data quality issues associated with this research project. Some of these limitations include:

1. Data Preparation: The OSM dataset and census tract data will require careful cleaning and processing. Spatial join operations and data aggregation may be necessary to ensure compatibility and meaningful analysis.

2. Outliers: Outliers, such as cafes located at JFK Airport or areas with a high number of cafes but a low population, may need to be removed from the analysis to avoid skewing the results.

3. Data Completeness: The OSM dataset may not capture all cafes in NYC, as it contains only 2591 observations out of an estimated ~3,600 coffee shops. This limitation should be considered when interpreting the findings.

Despite these limitations, the project aims to focus on the methodology and provide valuable insights into the clustering of third wave and local cafes in NYC.

## Conclusion
In conclusion, this research project on the clustering of third wave and local cafes in NYC offers valuable insights into the spatial patterns and factors driving the growth of the city's cafe culture. By utilizing GIS tools, spatial analysis techniques, and demographic data, the project provides a comprehensive understanding of the dynamics shaping the distribution of these cafes.

Through the interactive map and static maps, viewers can visually explore the clusters of cafes and their relationship with surrounding demographic characteristics. This information is crucial for cafe owners, urban planners, and policymakers in making informed decisions related to cafe locations, community development, and targeted marketing strategies.

Despite the limitations of the data, including potential outliers and data completeness issues, the project focuses on the methodology and establishes a solid foundation for future research in this field. By addressing the research questions regarding clustering, demographic influences, and travel distances, this study contributes to the scholarly understanding of the evolving coffee industry and its impact on urban environments.

The findings of this research can pave the way for further investigations, allowing researchers, practitioners, and stakeholders to delve deeper into the socio-economic aspects of cafe clustering, customer behavior, and the implications for local communities. Ultimately, this research project aims to provide valuable insights and recommendations that can shape the future development and sustainability of the cafe industry in NYC.

## Interactive Map: 
<iframe src= "map.html" height= "855" width= "95%">
</iframe>


## Static Maps:
<div style="display: flex;">
  <img src="map1.png" style="width: 50%; height: auto;">
  <img src="map2.png" style="width: 50%; height: auto;">
</div>

