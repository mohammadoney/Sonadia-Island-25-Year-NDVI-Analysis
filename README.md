# Sonadia-Island-25-Year-NDVI-Analysis

Data Preparation:
MODIS NDVI extraction from Google Earth Engine (MOD13Q1, 2000-2024)
Annual mean calculation from 16-day composites for 25 years
Missing data gap-filling using spatial interpolation
Island masking to focus analysis on Sonadia Island specifically

Analysis:
Temporal trend analysis: Mann-Kendall test with Sen's slope for island-wide NDVI
Spatial pattern analysis: Pixel-wise trend magnitude (Sen's slope) and significance (Mann-Kendall Z-score) mapping
Statistical validation: Confidence levels (95%, 99%) for detected changes

Results & Interpretation:
Overall significant greening: +0.007 NDVI/year trend (p < 0.001)
Spatially divergent patterns: Northern/eastern coasts show strong greening; southern/western coasts show significant browning
Management implications: Differential vegetation dynamics suggest varying environmental pressures across the island
