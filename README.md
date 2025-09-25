# GHCN Climate Data Analysis with Apache Spark

## Overview
This project explores the **Global Historical Climatology Network (GHCN) dataset** using **PySpark** on Azure.  
It demonstrates distributed data processing, analysis of daily climate elements, and geospatial visualisation of rainfall and temperature trends.  
Developed as part of the Scalable Data course (Big Data on Azure).

## Features
- Processed multi-gigabyte CSV datasets using **Apache Spark**  
- Built enriched station metadata tables (129,657 stations)  
- Analyzed coverage of 5 core climate elements (PRCP, TMIN, TMAX, SNOW, SNWD)  
- Detected data gaps and mismatches (e.g., TMIN vs TMAX)  
- Produced station-level summaries and global rainfall maps  

---

## Tech Stack
- **Languages:** Python, SQL  
- **Frameworks/Tools:** PySpark, Azure Data Lake, Jupyter, Pandas, Matplotlib, GeoPandas  
- **Data:** Global Historical Climatology Network (NOAA GHCN)  

---
## Visuals

- Global Rainfall Choropleth  
  ![Choropleth](visuals/Choropleth_map.png)

- Annual Average TMIN & TMAX (New Zealand)  
  ![Annual TMIN/TMAX](visuals/Annual_average_TMIN_and_TMAX.png)

- National TMIN & TMAX Time Series  
  ![Time Series](visuals/Annual_average_TMIN_and_TMAX_timeseries.png)

- Weather Stations in New Zealand  
  ![Stations Map](visuals/Weather_stations_map.png)
  

## Project Structure
ghcn-spark-analysis/
│── notebooks/                 # Jupyter notebooks with Spark analysis
│    ├── ghcn-spark-analysis.ipynb
│── visuals/                   # Exported plots and maps
│    ├── weather stations map.png
│    ├── Annual average TMIN and TMAX time series.png
│    ├── Annual average TMIN and TMAX.png
│    ├── Choropleth map
│── requirements.txt           # Python dependencies
│── README.md                  # Documentation
