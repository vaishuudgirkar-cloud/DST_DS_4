# DST_DS_4
 after running the notebook (will be created by the notebook).
- `accident_hotspot_map.html` — Heatmap HTML (generated if folium is available and lat/lng present).
- `README.md` — This file.

## How to use
1. Place your accident CSV in the same folder (common filenames: `US_Accidents_Dec20.csv`, `US_Accidents.csv`, `accidents.csv`).
2. Open the notebook in Google Colab or Jupyter.
3. Run cells sequentially.
4. For map visualizations, install folium (`pip install folium`) and ensure latitude/longitude columns exist in your dataset.

## Dataset suggestions
- **US Accidents (2016 - 2023)** by Sobhan Moosavi (Kaggle) — large countrywide dataset with lat/lng, severity, weather, etc.
- Local government open-data CSVs (e.g., data.gov) also work if they contain coordinates and weather/road condition columns.

## Notes
- The notebook is adaptive: it will try to detect time, location, weather, and road columns. You may need to adjust column names depending on your dataset.
- If dataset is large, sample or increase memory for faster plotting (maps especially).

---
Author: Vaishnavi
