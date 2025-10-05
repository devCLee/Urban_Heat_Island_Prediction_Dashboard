# NASA SPACE APPS SEOUL 2025
# Team Skyscraper: Urban Heat Island Prediction Dashboard

## Project Overview

The **Urban Heat Island Prediction Dashboard** is an interactive, data-driven tool designed to predict, visualize, and analyze urban heat island (UHI) phenomena. Utilizing advanced machine learning models and geospatial data processing, the dashboard provides actionable insights into temperature anomalies, helping city planners, researchers, and citizens understand and mitigate the effects of UHIs in metropolitan areas.

## Usage
```
streamlit run app.py
```

## Functionality

The dashboard fuses historical temperature records, land use data, and satellite imagery to forecast urban heat patterns at a granular scale. Users can interact with an intuitive map interface, explore heat intensity overlays for various city regions, and examine predictive analytics powered by robust ML models. Major features include:

- **Dynamic heat maps:** Visualize predicted temperature hotspots with temporal context.
- **Custom region selection:** Users select districts or points of interest to review local UHI predictions.
- **Overlay controls:** Toggle NASA data applied custom tileset layer of forest loss for multi-factor analysis.

![app_image_1](https://assets.spaceappschallenge.org/media/images/app_image_1.width-1024.png)
![app_image_2](https://assets.spaceappschallenge.org/media/images/app_image_2_jDXoc8Y.width-1024.png)
![app_image_3](https://assets.spaceappschallenge.org/media/images/app_image_3_ssetMek.width-1024.png)
![app_image_4](https://assets.spaceappschallenge.org/media/images/app_image_4.width-1024.png)

## Benefits

- **Policy Support:** Equips urban planners and policymakers with accurate, high-resolution forecasts to target cooling interventions (e.g., green infrastructure, zoning changes).
- **Public Engagement:** Raises awareness on climate resilience and the spatial distribution of urban heat, fostering community-driven action.
- **Research Advancement:** Facilitates academic studies on UHI drivers and temporal evolution via accessible spatial datasets and predictive tools.

## Intended Impact

The project aims to:

- Reduce the health risks and energy costs associated with urban heat buildups.
- Inform sustainable city design by highlighting areas in greatest need of interventions.
- Promote evidence-based decision-making to enhance urban livability amidst rising global temperatures.

## Technical Stack

- **Programming Languages:**  
  - Python (Jupyter Notebook, data preprocessing, model training)
- **Frameworks/Libraries:**  
  - Scikit-learn (ML algorithms)
  - Pandas, NumPy (tabular and timeseries data handling)
  - Folium, Plotly, or Streamlit (dashboard and map visualizations)
- **Geospatial Data Tools:**  
  - GeoPandas (spatial joins and operations)
  - Mapbox or Leaflet (interactive mapping and tile overlays)
- **Data Sources:**  
  - World Resources Institute (WRI) Data Explorer (Global drivers of forest loss at 1 km resolution - Version 1.2)
  - Microsoft Planetary Computer STAC API (Landsat 8, Sentinel-2, Sentinel 1, USGS 3DEP Lidar DSM/DTM/HAG)
  - Center for Open Science (Ground temperature data over New York City on July 24, 2021)

## Creativity and Distinctiveness

- **Integrated Predictive Analytics:** Combines spatial and temporal machine learning models for real-world UHI forecasting—unlike static visualizations, users see predictions of urban heat island hotspots and can simulate interventions.
- **Custom Tilesets and Map Layers:** Uses bespoke Mapbox tilesets for precise geographic detail and multi-layer visualizations, allowing users to contextualize heat intensity alongside urban features.
- **User-Centric Interactivity:** Designed for accessibility by technical and non-technical stakeholders, facilitating broad engagement and impact.

## Project Planning and Team Considerations

- **Data Availability and Quality:** Sought out high-resolution, recent datasets to ensure reliable predictions.
- **Scalability:** Designed modular pipelines—easy to expand to other cities or incorporate new data without major overhaul.
- **Ethical Review:** Considered privacy in publicly displayed location data; prioritized open data sources and algorithms for transparency.

***

## Conclusion  
The Urban Heat Island Prediction Dashboard demonstrates an innovative application of machine learning and geospatial visualization for urban climate resilience. Through this interactive tool, stakeholders can identify vulnerabilities, predict future hotspots, and design smarter cities for a warming world.

***
