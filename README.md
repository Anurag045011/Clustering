
# Vehicle Segmentation through K-Means Clustering

## Overview
This repository contains the code and report for the project on Vehicle Segmentation through K-Means Clustering. The project aims to segment vehicle data using unsupervised machine learning clustering algorithms, specifically K-Means clustering. It includes data preprocessing, analysis, and interpretation of clustering results.

## Project Objectives
1. Segmentation of Vehicle Data using Unsupervised Machine Learning Clustering Algorithms
2. Identification of Appropriate Number of Segments or Clusters
3. Determination of Segment or Cluster Characteristics

## Description of Data
- **Data Source**: [Car Dekho](https://www.cardekho.com/used-cars+in+delhi-ncr)
- **Data Size**: 7.16 MB
- **Data Shape**: 84,340 rows × 8 columns
- **Variables**: 
  - Categorical: Fuel, Seller Type, Transmission, Owner
  - Non-Categorical: Selling Price, Kilometers Driven

## Files
- `045011_Kmeans_Clustering.ipynb`: Google Colab Notebook containing the code and report for the project.
- `CAR DETAILS FROM CAR DEKHO.csv`: Dataset used for analysis.

## Requirements

- `Python 3.x`
- `Google Colab Notebook`
- `Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn`

## Usage
1. Clone the repository: `git clone https://github.com/Anurag045011/Clustering.git`
2. Install the required dependencies: `Given at the starting of the Google Colab Notebook after Report`
3. Open and run the Jupyter Notebook `045011_Kmeans_Clustering.ipynb` to explore the project code and analysis.

## Results
- The optimal number of clusters (K) is determined using the Elbow method and silhouette score analysis.
- Cluster characteristics and interpretations are provided based on centroid values and ANOVA results.
- Chi-Square Test of Independence is performed to analyze associations between categorical variables and clusters.

## Conclusion
The project provides insights into customer segmentation, marketing strategies, and inventory management for vehicle dealerships based on clustering analysis.




