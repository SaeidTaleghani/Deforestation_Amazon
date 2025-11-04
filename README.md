# 🌳 Amazon Deforestation Analysis (2010-2024)
A comprehensive Earth Engine-based analysis of deforestation patterns in the Amazon rainforest using MODIS satellite imagery and advanced geospatial processing.

📊 Project Overview

This project monitors and visualizes vegetation changes in the Amazon Basin over a 15-year period (2010-2024) using Google Earth Engine, Python, and remote sensing data. The analysis provides crucial insights into deforestation trends, vegetation health, and environmental impacts through multiple visualization techniques.

 ## Key Features
 - **Multi-temporal Analysis**: 15-year comprehensive study (2010-2024)
- **Dual Vegetation Indices**: NDVI (Normalized Difference Vegetation Index) and EVI (Enhanced Vegetation Index)
- **Automated GIF Generation**: Animated visualizations showing temporal changes
- **Deforestation Detection**: Custom algorithms to identify vegetation loss
- **Statistical Reporting**: Quantitative analysis of deforestation areas and percentages
- **Interactive Maps**: Split-panel comparisons and change detection maps

## Data Processing
1. **Annual Composites**: Median vegetation indices for each year
2. **Change Detection**: Pixel-wise comparison against 2010 baseline
3. **Threshold Classification**:
   - Severe Loss (ΔNDVI < -0.15)
   - Moderate Loss (ΔNDVI -0.15 to -0.05)
   - Stable Vegetation (ΔNDVI -0.05 to 0.05)
   - Vegetation Gain (ΔNDVI > 0.05)

## Vegetation Indices

- **NDVI**: Normalized Difference Vegetation Index
- **EVI**: Enhanced Vegetation Index (better sensitivity in high biomass regions)

