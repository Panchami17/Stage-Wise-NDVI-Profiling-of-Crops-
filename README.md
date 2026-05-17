# Stage‑Wise NDVI Profiling of Crops

## 📌 Project Overview
This project focuses on stage‑wise NDVI (Normalized Difference Vegetation Index) profiling of rice, maize, and wheat in Belagavi (2025–2026).  
The workflow integrates **Sentinel‑2 satellite imagery**, **Google Earth Engine**, and **Python (Colab environment)** to analyze crop phenology across sowing, vegetative, reproductive, and harvest stages.

## ⚙️ Workflow
The NDVI analysis pipeline is structured as follows:
1. **Inputs**  
   - Region of Interest (Belagavi)  
   - Crop calendar dates  
   - Manual crop polygons  

2. **Data Collection**  
   - Sentinel‑2 imagery (Jan 2025 – May 2026)  

3. **Pre‑Processing**  
   - Cloud masking  
   - NDVI calculation  

4. **Stage‑Wise Filtering**  
   - Sowing stage  
   - Vegetative stage  
   - Reproductive stage  
   - Harvest stage  

5. **Analysis**  
   - NDVI composites per crop  
   - Polygon mean extraction  
   - Statistical reducers (Min, Max, Mean)  

6. **Outputs**  
   - **Mean NDVI Trends** (line graphs showing crop‑specific growth patterns)  
   - **NDVI Range Statistics** (bar charts highlighting variability across farms)  

## 📊 Key Findings
- **Wheat** peaks during the vegetative stage, showing strong canopy vigor.  
- **Rice** demonstrates a steady increase in NDVI until harvest, reflecting prolonged greenness.  
- **Maize** maintains moderate NDVI values, with variability during reproductive growth.  
- Range analysis highlights differences between farms due to sowing dates, soil conditions, and management practices.

## 🛠️ Tools & Technologies
- Google Colab  
- Google Earth Engine  
- Python (NumPy, Pandas, Matplotlib)  
- Sentinel‑2 satellite datasets  

## 🎯 Applications
- Crop identification and monitoring  
- Phenology mapping for rice, maize, and wheat  
- Supporting precision agriculture and academic research  

---

👩‍💻 *Developed during internship at NITK Surathkal as part of research on crop phenology and NDVI visualization.*
