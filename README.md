# Baku Transportation Analysis

This project consists of two main parts: **Bus Stop Analysis** and **Bike Lane Analysis** in Baku, Azerbaijan. The analyses focus on public transportation accessibility and bike infrastructure.

---

## 1. Bus Stop Analysis

### 1.1 Collecting Bus Stop Information
I collected bus stop data from **OpenStreetMap** using **OSMnx**.  

### 1.2 Collecting University Information
Educational institutions (universities, colleges, and lyceums) were also collected from OSMnx. Polygon campuses were converted to centroids for accurate distance calculation.  

### 1.3 Distance Analysis and Insights
I calculated the distance from each educational institution to the nearest bus stop.  
- Institutions located more than **500 meters** from a bus stop were identified.  
- **Insight:** These areas show where public transportation access could be improved for students, highlighting potential opportunities for better service coverage.  

---

## 2. Bike Lane Analysis

### 2.1 Collecting Bike Lane Information
Bike lane data was collected from **OpenStreetMap data**.  

### 2.2 Loading Regions Dataset
District boundaries were loaded from **opendata.az** for spatial aggregation.  

### 2.3 Length Analysis and Insights
- Maximum bike lane length is in **Mardəkan**.  
- **Sabail District** has the longest total bike lanes.  
- One bike lane crosses **two districts**, showing inter-district connectivity.  

---
## Data Sources
- Bus stops & Universities: OpenStreetMap (via OSMnx)
- District boundaries: opendata.az

## Key Skills Demonstrated
- Geospatial data collection and processing
- Distance analysis using GeoPandas
- Mapping and visualization with Folium
- Identifying gaps in public transportation and bike infrastructure
- Aggregation and spatial analysis by district
