# 📍 CO₂ Storage Site Selection using Synthetic Geospatial Analysis

This project simulates a geospatial analysis pipeline to identify ideal sites for carbon dioxide (CO₂) storage. It uses **synthetic data** to demonstrate how spatial filtering can be applied based on geological, hydrological, and socio-environmental constraints.

---

## 🧪 Project Highlights

- Simulated **geological formations** (e.g., sedimentary basins).
- Synthetic **groundwater sensitivity** data to exclude high-risk areas.
- Mock **populated zones** to avoid proximity to human settlements.
- Filtering based on **depth suitability** for subsurface CO₂ storage.

---

## 📁 Output

An Excel file with multiple sheets:
- `Geology`: Formations with suitability tags.
- `Groundwater`: Sensitivity points with random scores.
- `Populated Areas`: Buffers around mock settlements.
- `Candidate Sites`: Final selected sites suitable for CO₂ storage.

---

## 🛠️ Tools Used

- `Python 3.9+`
- `GeoPandas`
- `Shapely`
- `Matplotlib`
- `NumPy`
- `XlsxWriter`

---

## 🚀 How to Run

1. Install dependencies:

```bash
pip install geopandas shapely matplotlib numpy xlsxwriter
Run the Python script:

bash
python co2_storage_analysis.py
Open the generated Excel file:


co2_storage_synthetic_analysis.xlsx
🧠 Potential Extensions
Replace synthetic data with real datasets (e.g., USGS geological layers).

Integrate raster data (e.g., porosity maps) using rasterio.

Use machine learning for site classification.

Perform web-based visualization with folium or leaflet.js.

📜 License
This project is for educational and demonstration purposes. No real-world decisions should be based on the synthetic results.

🤝 Author
Tarinabo williamtarinabo@gmail.com
