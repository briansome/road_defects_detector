Road Defect Detection Using YOLOv8
This repository presents an end-to-end deep learning pipeline for road defect detection, developed using YOLOv8 Small and Medium models. 
The system identifies and localizes common pavement anomalies such as cracks, potholes, rutting, and surface breaks.
It is designed for use in automated inspection tools, robotics perception modules, and infrastructure management systems.

1. Project Overview
Manual road inspection is slow, costly, and prone to inconsistency. This project provides a reproducible computer vision solution capable of detecting road defects in real time. By training YOLOv8-s and YOLOv8-m models on a richly diverse dataset, the system achieves reliable detection performance suitable for deployment on both edge hardware and GPU-based servers.
Project goals include:
High-accuracy detection of multiple defect types.
Stable real-time inference performance.
Comparative analysis between YOLOv8 Small and Medium variants.
Modular training, evaluation, and inference scripts.

2. Dataset
The dataset for this project was manually collected by the author, ensuring authentic road-surface variability and real-world defect representation. Images were captured across different locations, lighting conditions, and weather situations to maximize robustness and generalizability.

3. Model Architecture
Two YOLOv8 variants from Ultralytics were used:
YOLOv8-Small (YOLOv8-s)
Lightweight backbone
ast inference and deployable on edge devices
Lower computational demand
YOLOv8-Medium (YOLOv8-m)
Larger model with improved feature extraction
Higher accuracy at increased GPU cost
Suitable for cloud inference or offline batch processing
Both models were trained on the same dataset and hyperparameters to enable a fair and controlled comparison.

4. Training Pipeline
Training was conducted using the Ultralytics YOLO Python
