# Illegal Fishing Detection in Marine Protected Areas (MPAs)

This project leverages geospatial data analysis and satellite imagery to identify potential illegal fishing activities in Marine Protected Areas (MPAs). By integrating and analyzing vessel detection data from Sentinel-1 SAR and marine protected area shapefiles, we generate insights that support conservation efforts and enforcement actions.

---

## Introduction

Illegal, unreported, and unregulated (IUU) fishing is a global challenge that threatens marine biodiversity and sustainability. This project uses advanced data processing and spatial analysis techniques to detect and visualize potential IUU fishing activities within MPAs.

The main objectives of this project include:
- Processing and cleaning vessel detection data.
- Integrating Marine Protected Area (MPA) boundaries for geospatial analysis.
- Identifying high-risk vessels based on their behavior and locations.
- Generating visualizations to reveal patterns, trends, and potential illegal fishing hotspots.

---

## Features

- **Data Preprocessing**: Cleaned and merged large datasets of satellite-detected vessels and MPA shapefiles.
- **Spatial Analysis**: Performed spatial joins to detect vessels operating within MPAs.
- **Time-Series Analysis**: Analyzed temporal patterns of vessel activity.
- **Interactive Visualizations**: Created geospatial and time-series visualizations to highlight illegal fishing patterns.
- **High-Risk Vessel Identification**: Used fishing likelihood scores to pinpoint potential IUU fishing activities.

---

## Technologies Used

- **Python**: Data manipulation and analysis (`pandas`, `geopandas`, `numpy`).
- **Geospatial Libraries**: `shapely`, `matplotlib`, `Fiona`, `pyproj`.
- **Visualization Tools**: `matplotlib`, `seaborn`.
- **Data Sources**: Sentinel-1 SAR, Global Fishing Watch datasets, and Protected Planet MPA shapefiles.

---

## Datasets

### 1. **Sentinel-1 SAR Vessel Detections**
   - Source: [Global Fishing Watch](https://globalfishingwatch.org/)
   - Contains data on vessel locations, lengths, and fishing likelihood.

### 2. **Marine Protected Area (MPA) Shapefiles**
   - Source: [Protected Planet](https://www.protectedplanet.net/)
   - Includes geographic boundaries of MPAs.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/illegal-fishing-detection.git


## Results and Insights
Spatial Analysis:

Detected 2,600+ high-risk vessels operating within MPAs.
Identified hotspots of illegal fishing activity.
Temporal Trends:

Monthly time-series visualizations revealed seasonal peaks in vessel activity.
Visual Outputs:

Geospatial heatmaps and vessel trajectories for intuitive insights.
