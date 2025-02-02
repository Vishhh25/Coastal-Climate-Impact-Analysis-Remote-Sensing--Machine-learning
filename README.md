
# 🌍 Coastal Climate Impact Analysis using Machine Learning & Remote Sensing

## 📌 Project Overview
This project investigates the impact of **climate change on coastal ecosystems** using **machine learning (ML), deep learning (DL), and remote sensing techniques**. It leverages **Google Earth Engine (GEE), GIS-based analysis, and satellite imagery (Sentinel-2, MODIS, Landsat-8)** to model coastal changes due to **sea level rise, temperature variations, and habitat degradation**.

## 🚀 Features & Objectives
- 🌎 **Geospatial Analysis**: Remote sensing-based monitoring of coastal changes.
- 📡 **Satellite Data Processing**: Analyzing Sentinel-2, MODIS, and NOAA datasets.
- 🔥 **Machine Learning Models**: XGBoost, Random Forest, Gradient Boosting.
- 🧠 **Deep Learning Techniques**: LSTM for time-series forecasting.
- 🗺 **GIS Mapping & Visualizations**: Coastal risk assessment using heatmaps.
- 📊 **Climate Change Predictions**: Forecasting temperature, sea-level rise, and biodiversity impact.

## 📂 Project Structure
```
📦 Coastal-Climate-Impact-Analysis
│-- 📁 data/                  # Raw & processed datasets
│-- 📁 models/                # Trained ML & DL models
│-- 📁 notebooks/             # Jupyter Notebooks with analysis
│-- 📁 reports/               # Research reports, results, and visualizations
│-- 📜 Coastal_Climate_Impact_Analysis.ipynb   # Main Jupyter Notebook
│-- 📜 requirements.txt       # Required dependencies
│-- 📜 README.md              # Project documentation
│-- 📜 LICENSE                # Open-source license
```

## 🛠 Installation & Setup
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/Coastal-Climate-Impact-Analysis.git
cd Coastal-Climate-Impact-Analysis
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Authenticate Google Earth Engine (Optional)**
If using **Google Earth Engine (GEE)**, authenticate:
```python
import ee
ee.Authenticate()
ee.Initialize()
```

### **4️⃣ Run the Jupyter Notebook**
```bash
jupyter notebook Coastal_Climate_Impact_Analysis.ipynb
```

## 📊 Datasets Used
1. **Sentinel-2 (ESA)** - Multispectral imagery for land cover classification.
2. **MODIS (NASA)** - Ocean temperature and environmental anomaly tracking.
3. **Landsat-8 (USGS)** - Historical coastal change data.
4. **NOAA Climate Data** - Sea level rise and climate patterns.

## 🧑‍💻 Machine Learning & AI Models Used
### **Supervised Learning Models**
- ✅ **Random Forest Regressor** - Predicts climate-induced stress levels.
- ✅ **XGBoost** - Optimized tree-based model for temperature trend prediction.
- ✅ **Gradient Boosting Regressor** - Used for flood risk analysis.
- ✅ **Stacking Regressor** - Combines multiple ML models for better accuracy.

### **Deep Learning Approaches**
- 🧠 **LSTM (Long Short-Term Memory Networks)** - Forecasts sea surface temperature variations.
- 🖼 **CNNs (Convolutional Neural Networks)** - Image classification for coastal erosion patterns.

## 📡 Remote Sensing & GIS Methods
- 🛰 **NDVI (Normalized Difference Vegetation Index)** - Vegetation health monitoring.
- 🌊 **Sea Surface Temperature (SST) Mapping** - Detecting temperature anomalies.
- 🗺 **Coastal Risk Assessment** - Flood modeling using Digital Elevation Models (DEM).
- 📡 **Multi-Temporal Satellite Image Analysis** - Change detection over time.

## 🖼 Visualizations & Results
- 🔥 **Climate Anomaly Heatmaps**
- 🌎 **Coastal Erosion Detection using Sentinel-2**
- 📊 **Feature Importance Plots for ML Models**
- 🌊 **Sea Surface Temperature Change Over Time**
- 🗺 **GIS-Based Flood Risk Mapping**

## 📜 Future Enhancements
🚀 To improve this project, future work may include:
- **Integration of Real-Time Satellite Data** using IoT-based sensors.
- **AI-Based Coastal Monitoring Dashboard** for real-time climate impact tracking.
- **Expansion to Global Coastal Regions** for wider impact assessment.

## 🤝 Contributing
We welcome contributions! Please fork this repository and submit a pull request.

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b new-feature`)
3. **Commit your changes** (`git commit -m "Added new feature"`)
4. **Push to GitHub** (`git push origin new-feature`)
5. **Create a Pull Request**


## ✨ Acknowledgments
- **NASA EarthData & USGS** for providing open-source climate data.
- **Google Earth Engine (GEE)** for satellite image processing.
- **Scikit-Learn, TensorFlow, and XGBoost** for machine learning models.

## 📬 Contact
🔹 **Vishwa Raval**  
🔹 **Your Email: ravalvishwa2501.com**  

