# HDB Price Projection ML

<div align="center">

![Python](https://img.shields.io/badge/Python-3.14.0-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-blue?logo=jupyter)
![Version](https://img.shields.io/badge/version-0.1-green)

</div>

---

### 🎯 Project Scope

- **Geography**: Singapore HDB estates
- **Property Type**: Resale flats only (2-room to Executive)
- **Time Period**: 2017-2024 transactions
- **Features**: Location, amenities, physical attributes, lease information

## 📖 About

A ML model to forecast future HDB resale prices based on historical data.

## 📋 Required dependencies

- pandas
- numpy

## 📋 Dataset

1. [HDB Resale Price Data (gov.sg)](https://data.gov.sg/datasets/d_8b84c4ee58e3cfc0ece0d773c8ca6abc/view)

### Amenity Data Sources
2. **MRT Stations**: OpenStreetMap
3. **Bus Stops**: OpenStreetMap
4. **Schools**: OpenStreetMap
5. **Shopping Malls**: OpenStreetMap
6. **Hawker Centres**: OpenStreetMap
7. **Wet Markets**: OpenStreetMap

### Generated Features
- Geocoded addresses (latitude/longitude)
- Distance to nearest amenities (meters)
- Amenity counts within 500m radius
- Inflation-adjusted prices (RPI-based)
- Storey categories (lower/middle/upper)
