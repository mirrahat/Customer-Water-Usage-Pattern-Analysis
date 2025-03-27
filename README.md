# Water Consumption Analysis & Forecasting

## Overview

This project analyzes potable water consumption across different suburbs and forecasts future demand using deep learning (LSTM). It includes data visualization and geospatial mapping to help improve water resource management.

## Dataset

- **Potable Water Consumption by Suburb (2018-2024) [CSV]** – Contains water consumption data for multiple suburbs over several years.
- **Suburb Boundaries [GeoJSON]** – Used for geospatial visualization and mapping.

## Key Analyses & Features

### Exploratory Data Analysis (EDA)

- Examines yearly trends in water consumption.
- Identifies suburbs with high and low water usage.
- Analyzes the correlation between suburb area size (_Shape\_\_Area_) and water consumption.

### Geospatial Visualization

- Creates an interactive choropleth map displaying suburb-wise water usage.
- Uses heatmaps to highlight high-demand areas.

### Time Series Forecasting (LSTM Model)

- Predicts future water consumption trends for better planning.
- Helps identify potential water shortages and inform resource allocation.

## Project Structure

## Project Structure

```
Water_Consumption_Analysis/
├── data/
│   ├── potable_water_usage.csv
│   ├── suburb_boundaries.geojson
├── notebooks/
│   ├── eda_analysis.ipynb
│   ├── forecasting.ipynb
│   ├── geospatial_analysis.ipynb
├── models/
│   ├── water_usage_model.h5
│   ├── scaler.pkl
├── visualizations/
│   ├── consumption_trends.png
│   ├── suburb_map.html
├── scripts/
│   ├── water_forecasting.py
│   ├── geospatial_visualization.py
├── requirements.txt
└── README.md
```

## Results & Insights

- Water consumption varies significantly between suburbs, with some areas using much more than others.
- Forecasting suggests an increasing trend in water consumption in high-density areas.
- Geospatial maps highlight consumption hotspots, helping in better planning for water distribution.

## Future Improvements

- Enhance forecasting by incorporating climate and population growth data.
- Integrate real-time data streams for dynamic water usage tracking.
- Improve GIS mapping with 3D visualizations and satellite data.

## Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **TensorFlow/Keras** (LSTM for forecasting)
- **GeoPandas, Folium** (Geospatial mapping)
- **Scikit-learn** (Regression & data analysis)

## Author

Mir Hasibul Hasan Rahat  
GitHub: https://github.com/mirrahat  
LinkedIn: www.linkedin.com/in/mir-rahat-2b2108147

## License

This project is open-source under the **MIT License**.
