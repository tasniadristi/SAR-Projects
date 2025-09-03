# SAR-Projects
# 🌐 SAR Projects – Remote Sensing with Sentinel-1

This repository contains my **SAR-based geospatial projects**, showcasing applications in **flood impact assessment** and **crop detection** using **Sentinel-1 SAR data** and **Google Earth Engine (GEE)**.

---

## Projects

### 1. Cyclone Amphan Flood Assessment
- **Objective:** Map flood-affected areas and quantify impacts on population and cropland during Cyclone Amphan (2020).  
- **Study Area:** Satkhira, Khulna, and surrounding coastal districts, Bangladesh  
- **Study Period:** Pre-event: May 5–15, 2020 | Post-event: May 21–31, 2020  
- **Key Findings:**  
  - Flooded area: **165,227 hectares**  
  - Exposed population: **362,450 people**  
  - Affected cropland: **20,049 hectares**  
- **Folder:** `Cyclone-Amphan-Flood-Assessment/`  
- **Methods:** Sentinel-1 SAR preprocessing, speckle filtering, terrain correction, water detection, change detection, and overlay with population/cropland data.  

### 2. SAR-Based Crop Detection
- **Objective:** Identify crop types and monitor crop growth using SAR time-series data.  
- **Methods:** Sentinel-1 VV/VH polarization time-series, supervised classification, and validation using reference data.  
- **Folder:** `Crop-Detection/`  

---

## Repository Structure

SAR-Projects/
│── Cyclone-Amphan-Flood-Assessment/
│ ├── data/
│ ├── notebooks/
│ ├── scripts/
│ ├── outputs/
│ └── README.md
│
│── Crop-Detection/
│ ├── data/
│ ├── notebooks/
│ ├── scripts/
│ ├── outputs/
│ └── README.md
│
└── README.md


---

## Tools & Technologies
- **Google Earth Engine (GEE)** – SAR data processing and mapping  
- **Sentinel-1 SAR** – VV/VH polarization for flood and crop monitoring  
- **Python / Jupyter Notebooks** – data processing, analysis, visualization  
- **QGIS / GIS analysis** – map visualization  

---

## License
[MIT License](LICENSE) – free to use, modify, and distribute with attribution.  

---

## Author
**Tasnia Nowrin**  
📧 Email: tasniannowrin@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/tasnia-nowrin-250972189
