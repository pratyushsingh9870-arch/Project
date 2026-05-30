# ♻️ Smart Waste Segregation System

> AI-powered waste classification system using Computer Vision and Deep Learning to automate waste sorting and improve recycling efficiency.


---

##  Overview

Waste segregation is a critical challenge in modern waste management systems. Manual sorting is time-consuming, expensive, and prone to human error, leading to poor recycling efficiency and increased environmental impact.

This project leverages **Computer Vision**, **Deep Learning**, and **YOLOv8** to automatically classify waste into Organic and Inorganic categories in real time. The system is designed for deployment in smart bins, recycling facilities, and smart city infrastructure.

---

##  Key Highlights

* Trained on **2,000+ annotated waste images**
* Achieved **94% mAP**
* Reached **96% Precision**
* Real-time inference at **30+ FPS**
* Optimized for edge deployment using model pruning and quantization
* Suitable for smart waste management applications

---

##  System Architecture

```text
Image Input
     │
     ▼
Image Preprocessing
     │
     ▼
YOLOv8 Object Detection
     │
     ▼
Waste Classification
     │
     ▼
Organic / Inorganic Output
```

---

## 📸 Model Predictions

### Organic Waste Detection

The model correctly identified organic waste with high confidence.

**Prediction:** Organic
**Confidence:** 97.88%

![Organic Prediction](assets/op2.png)

---

### Plastic Waste Detection

The model correctly identified plastic waste with high confidence.

**Prediction:** Plastic
**Confidence:** 97.10%

![ Prediction](assets/op3.png)

---

##  Performance Evaluation

### Classification Report

![Classification Report](assets/report(1).png)

### Performance Metrics

| Metric    | Value |
| --------- | ----- |
| Accuracy  | 98%   |
| Precision | 0.98  |
| Recall    | 0.98  |
| F1-Score  | 0.98  |
| FPS       | 30+   |

---



## ⚙️ Technology Stack

### AI & Machine Learning

* Python
* YOLOv8
* OpenCV
* NumPy
* Ultralytics

### Optimization

* Model Quantization
* Model Pruning

### Deployment

* Edge Computing
* Real-Time Inference

---

##  Project Structure

```bash
Smart-Waste-Segregation-System/
│
├── assets/
│   ├── op.png
│   ├── op2.png
│   ├── op3.png
│   └── report.png
│
├── notebooks/
├── dataset/
├── models/
├── results/
├── waste_segregation_using_image_classification.ipynb
└── README.md
```

---

##  Applications

* Smart Waste Bins
* Automated Recycling Systems
* Smart Cities
* Environmental Monitoring
* Municipal Waste Management
* Sustainable Waste Processing

---

##  Future Improvements

* Multi-class waste classification
* Plastic, Metal, Glass, Paper categorization
* Raspberry Pi deployment
* IoT-enabled smart bins
* Cloud dashboard for monitoring
* Mobile application integration

---

##  Author

**Pratyush Singh**

Computer Science Undergraduate | AI Engineer | Full-Stack Developer

* LinkedIn: [www.linkedin.com/in/pratyush9870](http://www.linkedin.com/in/pratyush9870)
* GitHub: github.com/pratyushsingh9870-arch


