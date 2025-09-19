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
