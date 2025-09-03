# 🌊 Cyclone Amphan Flood Assessment (2020) – Sentinel-1 SAR

This project maps the **flood impact of Cyclone Amphan (May 2020)** in Bangladesh’s coastal districts using **Sentinel-1 SAR data** and **Google Earth Engine (GEE)**. SAR imagery penetrates clouds, allowing near real-time disaster monitoring during cyclones.

---

## Study Area
- **Districts:** Satkhira, Khulna, and surrounding coastal areas  
- **Country:** Bangladesh  

## Study Period
- **Pre-event:** May 5–15, 2020  
- **Post-event:** May 21–31, 2020  

---

## Objectives
1. Map flood-affected areas using pre- and post-event SAR imagery.  
2. Quantify flood extent, exposed population, and affected cropland.  
3. Demonstrate how SAR-based analysis supports disaster preparedness and recovery planning.  

---

## Key Findings
- **Flooded area:** 165,227 hectares  
- **Exposed population:** 362,450 people  
- **Affected cropland:** 20,049 hectares  

*Example flood map:*  
*(Insert map image here, e.g., `outputs/flood_extent_map.png`)*  

---

## Methodology
1. **Data Acquisition:** Sentinel-1 SAR (VV polarization) via GEE  
2. **Preprocessing:**  
   - Speckle filtering  
   - Radiometric calibration  
   - Terrain correction  
3. **Water Detection:** Thresholding and classification  
4. **Change Detection:** Compare pre- and post-event images  
5. **Impact Assessment:** Overlay flood maps with population and cropland datasets  

---

## Repository Structure

Cyclone-Amphan-Flood-Assessment/
│── data/ # input or sample data (if shareable)
│── notebooks/ # Jupyter notebooks for analysis
│── scripts/ # GEE or Python scripts
│── outputs/ # maps, figures, results
└── README.md # this file


---

## Tools & Technologies
- **Google Earth Engine (GEE)** – SAR processing and mapping  
- **Sentinel-1 SAR** – VV polarization for flood detection  
- **Python / Jupyter Notebooks** – analysis and visualization  
- **QGIS / GIS tools** – map preparation  

---

## License
[MIT License](../LICENSE) – free to use, modify, and distribute with attribution.  

---

## Author
**Tasnia Nowrin**  
📧 Email: tasniannowrin@gmail.com  
🔗 LinkedIn: [https://www.linkedin.com/in/tasnia-nowrin-250972189](https://www.linkedin.com/in/tasnia-nowrin-250972189)
