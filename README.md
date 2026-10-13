# Observational Spatial Ecology & Connectivity Modeling
**Author:** David Oloyede  
**Research Focus:** Global Environmental Change & Ecosystem Dynamics  

---

## Overview
This repository contains a reproducible computational pipeline that quantifies 24-year forest fragmentation dynamics across the Afi Mountain–Cross River transboundary corridor in southeastern Nigeria. Designed to evaluate structural habitat connectivity for the critically endangered Cross River gorilla (*Gorilla gorilla diehli*), the project integrates cloud-based Earth Observation with scientific Python arrays to bypass proprietary GIS environments.

---

## 📂 Complete Portfolio Documentation

* **Full Written Report & Spatial Analysis:** [Download Complete PDF](documents/Afi_Cross_River_Connectivity_Report.pdf) 

---

## 💻 Module-by-Module Code Execution (Google Colab)
The analytical pipeline for this research is hosted in an interactive Google Colab environment.

* **Habitat Fragmentation & Least-Cost Routing:** Computes morphological landscape metrics—identifying a +481.2% patch count expansion and -83.0% mean patch area collapse—and executes Dijkstra graph traversal across a Multi-Criteria Evaluation (MCE) resistance surface to map a dispersal pathway with a 1.26 tortuosity index.  
  👉 [Open Colab Notebook](https://colab.research.google.com/drive/1HqzZBToLo2lwRGnyW6D8UvsDER8a0SmN#scrollTo=naq8TqImgSXr)

---

## 🛠️ Core Technical Stack
* **Cloud Processing:** Google Earth Engine (GEE) Python API
* **Spatial Analysis & Graph Routing:** `rasterio`, `scipy.ndimage`, `skimage.graph`
* **Numerical Landscape Ecology:** NumPy, SciPy
* **Primary Satellite Datasets:** Hansen Global Forest Change v1.12 (60 m resolution, UTM Zone 32N)
