
## Sentinel-1 SAR Data Analysis for Soil Roughness and Moisture Estimation

This project analyzes Sentinel-1 SAR data to estimate soil surface roughness and soil moisture. Using SAR imagery, it offers insights into environmental factors affecting soil and vegetation across multiple years. This is particularly useful for applications in environmental monitoring and agriculture.





## About The Project

Purpose: To estimate and analyze soil surface roughness and moisture over time using Sentinel-1 SAR data.

Features: Includes speckle noise reduction, roughness estimation (via PSD and fractal models), and moisture estimation using a Water Cloud Model (WCM).

Outcome: Visualizations and trend analysis of soil roughness and moisture, showcasing temporal variations and environmental impacts.


## Dataset Description

Source: Sentinel-1 SAR data from the Copernicus Open Access Hub.

Format: Georeferenced .tif files for each year from 2014 to 2023.

Content: SAR backscatter values in decibel (dB) scale, requiring preprocessing for roughness and moisture calculation.



## Documentation

[Project Report](https://github.com/AntarjitaAdhya/Soil-Moisture-Estimation-From-SAR-data/blob/main/Project%20Report.pdf)




## Process To Set Up and Run

Environment Setup: Install necessary libraries like rasterio, numpy, and matplotlib for SAR data handling, calculations, and visualization.

Data Acquisition: Download Sentinel-1 SAR data from a trusted source (e.g., Copernicus Open Access Hub).

Preprocessing: Convert SAR data from dB to linear scale, apply speckle filtering to reduce noise, and calculate roughness using selected methods (PSD-based or fractal analysis).

Analysis & Visualization: Compute metrics such as fractal roughness and coefficient of variation (CV) for each year, and generate comparative plots to assess variations over time.

Interpret Results: Use these visualizations to understand temporal changes in soil surface roughness and moisture, interpreting the impact on SAR backscatter.



