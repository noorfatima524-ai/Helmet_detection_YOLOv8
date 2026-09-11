# Helmet_detection_YOLOv8
# Helmet Detection System Using YOLOv8  An end-to-end Computer Vision project built as part of **AIRI Team PITB AI Internship - 
# Helmet Detection System Using YOLOv8

An end-to-end Computer Vision project built as part of **AIRI Team PITB AI Internship - Task 1**.

This system automatically detects helmet compliance for safety monitoring.

### 🎯 Problem Solved
Manual monitoring of helmet usage is inefficient. This system automates safety compliance to reduce accidents and enforce rules at traffic signals and construction sites.

### 📂 Dataset
- **Total Images:** 1702
- **Classes (3):** `helmet`, `no-helmet`, `person`
- **Source:** Roboflow Universe & Kaggle
- **Annotation:** Roboflow (YOLO Format)
- **Split:** 70% Train / 20% Val / 10% Test

### 🛠️ Tools & Tech
Python, Google Colab, YOLOv8, Ultralytics, OpenCV, Roboflow, Matplotlib

### 🚀 Model Training
- Model: YOLOv8n
- Epochs: 50, Img Size: 640, Batch: 16
- Platform: Google Colab T4 GPU
- Best weights: `best.pt`

### 📊 Evaluation
- Precision: 0.891
- Recall: 0.843
- mAP@0.5: 0.887
- mAP@0.5:0.95: 0.634

### 🔍 Inference
Tested on unseen images and videos. The model detects multiple objects with bounding boxes and confidence scores.

### 📉 Error Analysis
- Struggles with small/distant objects
- False positive when holding helmet vs wearing
- Low-light and blur affects detection

### 📚 What I Learned
- Large dataset handling and annotation
- YOLOv8 training and evaluation workflow
- Importance of data quality and error analysis

### 🔮 Future Improvements
- Add night-time data, train YOLOv8s/m
- Deploy as Streamlit Web App
- Real-time CCTV integration

### 🔗 Links
- **Model Weights:** [Drive Link]
- **Dataset:** [Drive Link]
