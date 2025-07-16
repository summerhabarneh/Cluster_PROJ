# Democracy Index Clustering Analysis

## Overview
An unsupervised machine learning project that was able to qualify different countries into distinct political regimes by analyzing various democracy indicators across 167 countries. 4 distinct regime categories were revealed using K-means and Hierarchical clustering 

## Key Findings
- **23%** of countries qualified as full democracies
- - score was > 8.0
- **29%** of countries fell under authoritarian regimes
- - score was < 4.0
- 4 clusters were validated using elbow method and silhouette analysis

## Dataset
- **Source**: Democracy Index 2023
- **Size**: 167 countries and 5 democratic indicators (total=835)
- **Features** :
- - Electoral process and pluralism
- - Functioning of government
- - Political participation
- - Political culture
- - Civil liberties

## Methodology
1. **Data Preprocessing**: StandardScalar for feature normalization
2. **Clustering Analysis**: K-means and hierarchical clustering comparisons
3. **Validation**: Elbow method, silhouette score(29.7%)

## Technologies
- Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn