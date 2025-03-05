# CryptoClustering

## Project Overview

This project applies K-means clustering and Principal Component Analysis (PCA) to uncover patterns in cryptocurrency price change data.

## Techniques

### Clustering Approaches
- Direct K-means clustering on raw price change percentages
- PCA-enhanced clustering with dimensionality reduction

### Data Preprocessing
- Standardized price change percentages across multiple time frames
- Applied Principal Component Analysis (PCA)
- Utilized K-means algorithm for grouping

## Key Insights

### Clustering Results
- Identified 4 distinct cryptocurrency clusters
- Analyzed price change patterns across 24h, 7d, 14d, 30d, 60d, 200d, and 1y time frames

### Principal Component Analysis Highlights
- PC1: Influenced by long-term price changes (200-day and 1-year percentages)
- PC2: Reflects mid-term price trends (14-day and 30-day percentages)
- PC3: Captures short-term price movement volatility

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- NumPy
