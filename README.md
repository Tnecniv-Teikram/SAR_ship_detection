# 🚢 SAR Ship Detection deep learning tutorial with Sentinel-1 data

### Synthetic Aperture Radar (SAR) for Maritime Monitoring

This repository contains a **hands-on tutorial notebook** demonstrating how to detect ships using **Synthetic Aperture Radar (SAR) imagery**. It is designed as part of the **Space Academy training series**, with a focus on practical geospatial workflows and real-world applications.

👉 **Open the notebook:**  
[View SAR Ship Detection Notebook](https://github.com/Tnecniv-Teikram/SAR_ship_detection/blob/main/space_academy_SAR_ship_detection.ipynb)

***

## 📌 Overview

Ship detection using SAR imagery is a key capability for:

* Maritime surveillance
* Illegal fishing detection
* Port activity monitoring
* Maritime safety and security

Unlike optical imagery, SAR works **day/night and in all weather conditions**, making it ideal for continuous monitoring. [\[datavlab.ai\]](https://datavlab.ai/post/sar-ship-detection-datasets)

In SAR images, ships typically appear as **bright, high-backscatter targets against darker ocean backgrounds**, enabling automated detection workflows. [\[datavlab.ai\]](https://datavlab.ai/post/sar-ship-detection-datasets)

***

## 🧭 What You Will Learn

This tutorial walks you through a complete SAR ship detection workflow:

### 1. Data Access & Loading

* Retrieve SAR imagery (e.g., Sentinel-1)
* Define area of interest (AOI)

### 2. Preprocessing

* Radiometric calibration and normalization
* Speckle noise considerations
* Image preparation for analysis

### 3. Feature Extraction

* Understand SAR backscatter characteristics
* Identify ship signatures vs ocean clutter

### 4. Detection Workflow

* Apply thresholding or detection logic
* Extract candidate ship objects
* Reduce false positives

### 5. Visualization & Interpretation

* Overlay detections on SAR imagery
* Interpret spatial patterns of vessel activity

***

## 🛰️ Why SAR for Ship Detection?

SAR provides unique advantages for maritime monitoring:

* ✅ Works **independently of sunlight and weather conditions** [\[datavlab.ai\]](https://datavlab.ai/post/sar-ship-detection-datasets)
* ✅ Detects vessels even without AIS signals
* ✅ High contrast between ships and ocean surface
* ✅ Suitable for large-scale, repeated monitoring

***

## 📁 Repository Structure

```
SAR_ship_detection/
│
├── space_academy_SAR_ship_detection.ipynb   # Main tutorial notebook
└── README.md                               # Project documentation
```

***

## ⚙️ Requirements

Typical Python environment for this tutorial includes:

* `numpy`
* `matplotlib`
* `rasterio`
* `geopandas`
* `folium` (optional for visualization)

Depending on your setup, you may also use:

* EO data APIs (e.g., Sentinel-1 access)
* SNAP / SAR processing tools (optional)

***

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/Tnecniv-Teikram/SAR_ship_detection.git
cd SAR_ship_detection
```

2. Open the notebook:

```bash
jupyter notebook space_academy_SAR_ship_detection.ipynb
```

3. Follow the step-by-step workflow inside the notebook

***

## 📊 Applications

The methods demonstrated here can be extended to:

* Ship density mapping
* Maritime traffic analysis
* Environmental monitoring (oil spills, illegal activity)
* Integration into larger EO pipelines

***

## 🎓 Target Audience

This tutorial is designed for:

* Remote sensing practitioners
* Data scientists working with EO data
* Space Academy participants
* Hackathon teams exploring SAR applications

***

## 🚀 Next Steps

After completing this tutorial, you can extend it by:

* Applying **deep learning (YOLO / CNN-based detection)**
* Scaling to **large AOIs and time series analysis**
* Integrating **AIS data for validation**
* Building **operational monitoring dashboards**

***

## 🤝 Acknowledgements

This tutorial builds on concepts from:

* ESA / Sentinel-1 SAR processing workflows
* Open SAR ship detection datasets and methodologies
* Geospatial and EO community best practices

***

## 📬 Contact

For questions, improvements, or collaboration:

* Open an issue in this repository
* Contribute improvements via pull request

***

If you want, I can **upgrade this README into a more “premium” version** (with diagrams, pipeline visuals, and hackathon branding aligned to your Space Academy slides).

