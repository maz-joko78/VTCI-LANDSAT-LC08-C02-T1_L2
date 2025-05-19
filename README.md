# VTCI-LANDSAT-LC08-C02-T1_L2
This repository contains a Google Colab notebook for calculating and visualizing the Vegetation Temperature Condition Index (VTCI) using Landsat 8 Level-2 data via Google Earth Engine (GEE) Python API. The VTCI is a remote sensing-based drought index that combines NDVI and LST to monitor agricultural drought.
Terima kasih, berikut deskripsi repository GitHub yang disesuaikan dengan akun kamu `maz-joko78` dan penggunaan **Google Colab** untuk analisis **VTCI (Vegetation Temperature Condition Index)**:

---

## 📗 VTCI Drought Analysis with Google Colab & Earth Engine

**Repository Name**: `vtci-drought-colab`
**Author**: [maz-joko78](https://github.com/maz-joko78)

### 📌 Description

This repository contains a **Google Colab notebook** for calculating and visualizing the **Vegetation Temperature Condition Index (VTCI)** using **Landsat 8 Level-2 data** via **Google Earth Engine (GEE) Python API**. The VTCI is a remote sensing-based drought index that combines **NDVI** and **LST** to monitor agricultural drought.

### 🚀 Key Features

* 🛰️ Uses **Landsat 8 Collection 2, Tier 1, Level-2** surface reflectance & temperature data
* 🧾 Cloud masking via **QA\_PIXEL** bits
* 📊 Calculates **NDVI**, **LST**, and **VTCI**
* 🎯 VTCI defined as:

  $$
  \text{VTCI} = \frac{LST_{\text{max}} - LST}{LST_{\text{max}} - LST_{\text{min}}}
  $$

  where:

  * **VTCI = 1** → wet condition
  * **VTCI = 0** → dry condition
* 🌍 Region of interest (AOI): Customizable (e.g., Mataram, Lombok)
* 📈 NDVI vs LST scatter plot with warm & cold edge regression (optionally visualized using matplotlib or chart libraries)

### 📁 Repository Structure

```
vtci-drought-colab/
├── vtci_analysis.ipynb         # Main Google Colab notebook
├── README.md                   # Project description
├── img/                        # Optional images for documentation
└── requirements.txt            # Python package dependencies (GEE, folium, etc.)
```

### 🧰 Requirements

* Google Colab (or Jupyter Notebook)
* Earth Engine Python API
* geemap / folium (for mapping)
* matplotlib / seaborn (optional for charts)

### 📚 References

* Wang et al. (2001). *A new method for drought monitoring: VTCI*
* Patel et al. (2011). *Assessment of agricultural drought using VTCI*
* Tang et al. (2010). *LST-NDVI Space Analysis*

### 🧑‍💻 Author

Repository developed and maintained by **[@maz-joko78](https://github.com/maz-joko78)** for drought monitoring research and educational purposes.


