# HDB Price Projection ML

<div align="center">

![Python](https://img.shields.io/badge/Python-3.14.0-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-blue?logo=jupyter)
![Version](https://img.shields.io/badge/version-0.1-green)

</div>

---

## 📖 About

A ML model to forecast future HDB resale prices based on historical data.

## 📋 Required dependencies

- pandas
- numpy

## 📋 Dataset

1. [HDB Resale Price Data (gov.sg)](https://data.gov.sg/datasets/d_8b84c4ee58e3cfc0ece0d773c8ca6abc/view)

### Amenity Data Sources
2. **MRT Stations**: OpenStreetMap / LTA DataMall
3. **Bus Stops**: LTA DataMall (5000+ stops with codes)
4. **Schools**: OpenStreetMap / MOE data
5. **Shopping Malls**: OpenStreetMap
6. **Hawker Centres**: NEA official list (123 centres)
7. **Wet Markets**: OpenStreetMap

### Generated Features
- Geocoded addresses (latitude/longitude)
- Distance to nearest amenities (meters)
- Amenity counts within 1km radius
- Inflation-adjusted prices (RPI-based)
- Storey categories (lower/middle/upper)
