# Frailty-Gait-STGCN

Official implementation of the manuscript:  
**“Graph Deep Learning with Attention for Gait-based Frailty Prediction”**  
*(Submitted to......)*


## Overview
This repository contains the code for an **attention-guided spatiotemporal graph convolutional network (ST-GCN)** designed to predict frailty from Kinect-based gait recordings.  

Key features:
- Hybrid ST-GCN with **joint- and frame-level attention**  
- **Interpretability** via Grad-CAM and attention heatmaps  
- **Patient-level decision fusion** (soft, attention-weighted, confidence-weighted, blended voting)  
- **Meta-classifier** for secondary prediction using XGBoost  
- Example scripts for preprocessing, training, testing, and visualization  

> Patient-level data cannot be shared due to privacy restrictions.


## Installation

Clone the repository:
```bash
git clone https://github.com/iqram20/Frailty-Gait-STGCN.git
cd Frailty-Gait-STGCN

```bibtex
@software{Hussain_FrailtyGaitSTGCN_2025,
  author       = {Iqram Hussain and Rodrigo Sarlo and Rafsan Jany and Julia Scarpa and Kane O. Pryor and Richard Boyer and Joseph Scarpa},
  title        = {Frailty-Gait-STGCN: Attention-Guided Graph Deep Learning for Interpretable Frailty Prediction from Gait},
  month        = sep,
  year         = 2025,
  publisher    = {Zenodo},
  version      = {v1.0.0},
  doi          = {10.5281/zenodo.17162373},
  url          = {https://doi.org/10.5281/zenodo.17162373}
}
