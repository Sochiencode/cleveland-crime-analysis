# cleveland-crime-analysis
Temporal, spatial and forecasting analysis of Cleveland Police crime data (2023–2025)

## Overview
This project analyses recorded crime data from the Cleveland A26 policing area between 2023 and 2025. The analysis combines exploratory data analysis, spatial hotspot mapping, and time-series forecasting to identify crime patterns and support intelligence-led policing insights.

The project focuses on understanding how crime volume, distribution, and trends evolve over time, with particular emphasis on Violence and Sexual Offences due to their public safety impact.

---

## Data Source
- UK Police open crime data  
- Cleveland Police (A26)  
- Monthly street-level crime datasets  

Data was collected and organised by year (2023–2025) and aggregated for analysis.

---

## Methods
The analysis follows a structured data-science workflow:

- **Data Preparation**
  - Multi-year ingestion and consolidation of monthly datasets
  - Standardisation of date fields and handling of missing values

- **Exploratory & Temporal Analysis**
  - Crime-type frequency analysis
  - Monthly aggregation and seasonality exploration
  - Heatmap visualisation of crime distributions

- **Spatial Analysis**
  - Interactive mapping using Folium
  - Marker clustering to identify high-density areas
  - Heatmap analysis to visualise persistent hotspots
  - Focused spatial analysis on Violence and Sexual Offences

- **Forecasting**
  - Monthly time-series modelling using Seasonal ARIMA (SARIMA)
  - Train/test split with short-term forecasting
  - Evaluation using MAE and RMSE metrics

---
## Visual Outputs

### Spatial Hotspot Analysis – Violence and Sexual Offences
The map below shows marker clustering and heatmap intensity for recorded Violence and Sexual Offences across the Cleveland A26 area.

![Violence and Sexual Offences Heatmap](assets/heatmap_vso.png)

---

### Marker Clustering of Crime Incidents
Marker clustering highlights areas with persistent concentrations of reported incidents.

![Marker Cluster Map](assets/marker_cluster_vso.png)

---

### Monthly Crime Trend
Monthly aggregated crime counts illustrate seasonality and temporal variation over the three-year period.

![Monthly Crime Trend](assets/monthly_trend.png)


## Key Findings
- Violence and Sexual Offences consistently represent one of the highest-volume crime categories
- Clear seasonal patterns are observable across multiple offence types
- Spatial clustering reveals persistent hotspots rather than isolated incidents
- Short-term forecasts indicate stable but elevated incident levels

---

## Limitations
- Open crime data may contain reporting delays or incomplete geographic coordinates
- The analysis does not establish causal relationships between policing strategies and crime levels
- Forecasts assume historical patterns remain stable over the short term

---

## Tools & Technologies
- Python
- pandas, NumPy
- matplotlib, seaborn
- Folium (spatial mapping)
- statsmodels (SARIMA forecasting)
- scikit-learn (evaluation metrics)
- Google Colab

---

---

## Author
**Ifesochi Abanum**  
MSc Crime Intelligence & Data Analysis  

---

## Use Case
This project demonstrates applied crime data analysis techniques relevant to roles in:
- Crime Analysis
- Intelligence Analysis
- Data Analysis
- Public Safety & Policy Research

