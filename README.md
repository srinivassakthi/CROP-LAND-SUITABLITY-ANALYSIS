# Crop Land Suitability Analysis for Thoothukudi District

Geospatial analysis system identifying optimal agricultural lands in Thoothukudi, Tamil Nadu using GIS and Multi-Criteria Decision Analysis.

## 📌 Introduction
This project addresses the critical need for sustainable agriculture by analyzing land suitability for crop cultivation. Using Analytic Hierarchy Process (AHP) and Weighted Overlay Analysis with GIS, we identify optimal farming locations to:
- Maximize crop yields
- Promote sustainable land use
- Enhance food security
- Optimize resource allocation

> "With only 30% of global land suitable for agriculture, precision land assessment becomes crucial for food security." - FAO

## 🎯 Objectives
1. Evaluate land suitability for diversified cropping
2. Assess terrain factors (slope, elevation, drainage)
3. Analyze soil characteristics (texture, moisture, geology)
4. Identify optimal zones for sustainable agriculture
5. Develop decision-support framework for farmers

## 📁 Dataset Overview
| Data Type | Source | Resolution | Key Parameters |
|-----------|--------|------------|----------------|
| Landsat 8 | USGS | 10m | NDVI, NDWI |
| SRTM DEM | USGS | 30m | Elevation, Slope |
| Soil Map | FAO | 1:2M | Texture, Composition |
| LULC Data | ESRI | 100m | Land Cover Classes |
| Geology | Bhukosh | 1:2M | Rock Formation |

## ⚙️ Methodology

    A[Raw Data] --> B(Preprocessing)
    B --> C[Data Standardization]
    C --> D[AHP Weighting]
    D --> E[Weighted Overlay]
    E --> F[Suitability Classification]

Factor Analysis: 9 parameters standardized (Slope, Aspect, Elevation, Soil Moisture, Drainage Density, Soil Type, Geology, Geomorphology, LULC)

AHP Weighting: Expert-driven pairwise comparisons

Weighted Overlay: Criteria integration using:

FAO Classification: Lands categorized as:

Highly Suitable (S1)

Moderately Suitable (S2)

Marginally Suitable (S3)

Not Suitable (N)

🔍 Key Findings
Suitability Class	Area (km²)	Percentage	Characteristics
Highly Suitable	1,386.3	30%	Optimal soil, gentle slopes, good drainage
Moderately Suitable	2,310.5	40%	Minor limitations in soil/texture
Marginally Suitable	693.15	15%	Steep slopes/low moisture
Not Suitable	231.05	5%	Coastal/rocky terrain
Critical Insights:

70% of land (3,696 km²) agriculturally viable

Northwest regions show highest elevation suitability

Coastal areas limited by salinity and moisture

Sandy loam soils (Luvisols) dominate productive zones

🛠️ Tools Used
ArcGIS/ QGIS (Data Visualization, Geoprocessing, Weighted Overlay)

Interactive Suitability Map

Parameter Analysis Charts

🌟 Conclusion
This study demonstrates that 70% of Thoothukudi's land can support sustainable agriculture when paired with appropriate farming techniques. The GIS-AHP framework provides policymakers and farmers with:

Precision land evaluation

Crop-specific suitability insights

Resource optimization strategies

Climate adaptation pathways

"Wise farming techniques could boost district's agricultural economy by 25-40%" - Project Findings
