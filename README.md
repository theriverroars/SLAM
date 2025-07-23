# Metric-Semantic SLAM and Object-Level Localization on the TCS-X Ground Floor

This repository contains the **final report** and **demonstration videos** for our course project in *Robot Perception* (May 2025), carried out as part of our M.Tech. program. The project focuses on comparing two prominent SLAM frameworks—**Kimera** and **RTAB-Map**—for indoor mapping and semantic localization using Intel RealSense data.

## 📌 Project Overview

We explore **Metric-Semantic SLAM** techniques to reconstruct a 3D map of the ground floor of the TCS-X building, using RGB-D input from an Intel RealSense camera. Our objectives:

- Generate accurate, semantically annotated maps
- Compare the performance of **Kimera** and **RTAB-Map**
- Evaluate localization accuracy using **Absolute Trajectory Error (ATE)**
- Perform **object-level localization** (e.g., couches, people) using segmentation

## 📄 Contents

- `Perception_report_Part_1__Falak_and_Ganga_.pdf`: Detailed technical report covering our methodology, results, and analysis.
- For videos refer: https://indianinstituteofscience-my.sharepoint.com/:f:/g/personal/falakfatima_iisc_ac_in/Eh4j7PTNXO1InAwmaEWQ_WwBF3Fdr1QTpbL60Ipvv_jqUQ?e=wiZo6u
## 🧠 Key Highlights

- **Kimera**: Provided accurate visual-inertial SLAM with dense semantic mesh reconstruction.
- **RTAB-Map**: Enabled real-time RGB-D SLAM with effective loop-closure detection and point cloud maps.
- **Segmentation Pipeline**: Used DeepLabV3 with ResNet-50 backbone to detect and localize indoor objects in real-time.

## 🧑‍💻 Authors

- **Falak Fatima (24349)**
- **Ganga Nair B (25565)**

Indian Institute of Science – M.Tech. in Robotics and Autonomous Systems

## 📚 Course

**Robot Perception**, Jan 2025  
Instructor: *[Dr. Bharadwaj Amrutur]*

---

> ⚠️ This repository does **not contain source code**. It serves as a documentation and media archive for the completed perception project.
