# Frailty-Gait-STGCN

Official implementation of the manuscript:  
**“Attention-Guided Graph Deep Learning for Interpretable Frailty Prediction from Gait”**  
*(Submitted to......)*

---

## 📖 Overview
This repository contains the code for an **attention-guided spatiotemporal graph convolutional network (ST-GCN)** designed to predict frailty from Kinect-based gait recordings.  

Key features:
- Hybrid ST-GCN with **joint- and frame-level attention**  
- **Interpretability** via Grad-CAM and attention heatmaps  
- **Patient-level decision fusion** (soft, attention-weighted, confidence-weighted, blended voting)  
- **Meta-classifier** for secondary prediction using XGBoost  
- Example scripts for preprocessing, training, testing, and visualization  

> ⚠️ Patient-level data cannot be shared due to privacy restrictions. A **synthetic demo dataset** is provided for reproducibility.  

---

## 🛠️ Installation

Clone the repository:
```bash
git clone https://github.com/iqram20/Frailty-Gait-STGCN.git
cd Frailty-Gait-STGCN
