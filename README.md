# Geospatial Analysis of Vocational Training Accessibility and Women's Economic Empowerment in Bekaa, Lebanon (2024-2026)

**Project Lead:** Rana Yassin  
**Tools Used:** ArcGIS (ArcMap 10.8), Tableau Public, Microsoft Excel  
**Region:** Bekaa Governorate (Zahle, West Bekaa, Rashaya)

## 📌 Project Overview
This project provides a comprehensive geospatial and data-driven analysis of the accessibility of Vocational Training Centers (VTCs) for women in the Bekaa region. By mapping the density of these centers against female unemployment and labor force participation rates, the study identifies critical "economic empowerment gaps," particularly in underserved districts like Rashaya.

## 🔍 Key Findings
*   **Correlation between Accessibility & Employment:** A strong negative correlation was identified between the density of VTCs and female unemployment rates.
*   **Rashaya District Crisis:** Rashaya has the lowest VTC density (only 3 centers) and the highest female unemployment rate (40.2%) in the governorate.
*   **Zahle District Success:** Zahle benefits from the highest VTC density (10 centers), resulting in the lowest female unemployment rate (32.8%) in the region.
*   **Spatial Gaps:** Kernel Density analysis reveals significant "cold spots" in rural West Bekaa and Rashaya, where travel distance acts as a major barrier to women's economic participation.

## 🛠 Methodology
1.  **Geospatial Analysis (ArcMap):**
    *   Kernel Density Estimation (Heat Map) to visualize VTC concentration.
    *   Buffer Analysis to determine service areas and accessibility zones.
    *   UTM Zone 36N projection for accurate distance measurements.
2.  **Data Analytics (Tableau):**
    *   Comparative analysis of unemployment rates by district.
    *   Correlation mapping between institutional availability and economic outcomes.
3.  **Data Processing (Excel):**
    *   Cleaning and structuring socio-economic indicators from regional reports.

## 📂 Repository Contents
*   `Data/`: CSV files including VTC locations and socio-economic indicators.
*   `Visuals/`: Professional GIS maps (Heat Maps) and Tableau charts.

## 💡 Recommendations
*   Prioritize the establishment of new mobile or permanent vocational training units in the **Rashaya** district.
*   Improve public transportation links between rural towns and existing centers in **Zahle**.
*   Tailor training programs to the specific economic needs of women in the **West Bekaa** region.

## 📚 Data Sources
*   **Economic Indicators:** Compiled from regional labor force surveys and household living conditions reports (2022-2024).
*   **Institutional Data:** Compiled from public records of Vocational and Technical Education institutions in Lebanon.
*   **Geospatial Layers:** GADM database and open-source municipal mapping data.

## ⚠️ Note on Data Accuracy
VTC locations are mapped based on available municipal data and town-level geocoding. While some coordinates represent town centers rather than exact building footprints, the spatial distribution remains accurate for regional density and accessibility analysis.
## 📊 Project Visuals & Maps

### 1. Kernel Density Heat Map (ArcGIS)
![Heat Map](heat%20map%20(2).jpg)

### 2. VTC Distribution & Charts (Tableau)
![VTC Distribution](Distribution%20of%20Vocational%20Training%20Centers%20(VTCs).png)
![Unemployment Rate](Female%20Unemployment%20Rate%20by%20District%20-%20Bekaa.png)
![Correlation](Correlation%20between%20VTC%20Availability%20and%20Female%20Unemployment.png)
