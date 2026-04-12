 Image-Based-Product-Price-Recognition-System
=================================================

<img src="https://github.com/Salma-Salah420/Image-Based-Product-Price-Recognition-System/blob/b09e509483de33b7e60ce7401c65755b1135eeb4/_%D8%B3%D9%88%D8%A8%D8%B1_%D9%85%D8%A7%D8%B1%D9%83%D8%AA_3.jpg" width="600"/>

The Image-Based Product Price Recognition System is a smart application that automatically detects products and their prices directly from images using computer vision techniques. It is designed to assist in retail analysis, price monitoring, and smart shopping solutions.
========
Features
========

Product Detection: Identify products in images using computer vision algorithms.

Price Recognition: Detect and read price tags from product images.

Multiple Products Handling: Works with images containing several products at once.

Data Export: Save extracted product names and prices in structured formats like CSV or JSON.

Cross-Platform: Works with images captured by mobile phones, cameras, or online sources.

Use Cases
=========

Automated price comparison between different stores.

Inventory management for retail businesses.

Shopping assistance applications.

Market research and analytics.

Technologies
============

Python & OpenCV for image processing and computer vision.

Image segmentation and contour detection for product and price localization.

Optional GUI or command-line interface for ease of use.

Models:
1. XGBoost:
----------
 Current Model Results (XGBoost)

| Metric | Training | Testing |
|--------|----------|---------|
| **R² Score** | 0.9991 | 0.9936 |
| **MAE (EGP)** | 3.29 | 6.62 |
| **RMSE (EGP)** | 5.15 | 14.58 |
| **MAPE (%)** | 3.54% | 6.15% |

XGBoost Performance Summary:
- R² = 99.36% → Excellent fit
- Average error = 6.62 EGP → Very low
- No significant overfitting
- ![losscurve](https://github.com/Salma-Salah420/Image-Based-Product-Price-Recognition-System/blob/9d6b26fb7246165c3bf7c1b591885f5cde6e96a1/outputs/loss%20curve.png)

  2.LSTM model:
  ---------------
| Metric | XGBoost | LSTM | Difference | Winner |
|--------|---------|------|------------|--------|
| **R² Score (Training)** | 0.9991 | 0.8296 | +0.1695 | ✅ XGBoost |
| **R² Score (Testing)** | 0.9936 | 0.8417 | +0.1519 | ✅ XGBoost |
| **MAE (Training)** | 3.29 EGP | 36.31 EGP | -33.02 | ✅ XGBoost |
| **MAE (Testing)** | 6.62 EGP | 38.80 EGP | -32.18 | ✅ XGBoost |
| **RMSE (Training)** | 5.15 EGP | 70.01 EGP | -64.86 | ✅ XGBoost |
| **RMSE (Testing)** | 14.58 EGP | 72.57 EGP | -57.99 | ✅ XGBoost |

![loss LSTM](https://github.com/Salma-Salah420/Image-Based-Product-Price-Recognition-System/blob/7409888b1be45158ddff926438e6cb634b092546/outputs/LSTM%20loss%20curve.png)

![loss lstm vs XGBoost](https://github.com/Salma-Salah420/Image-Based-Product-Price-Recognition-System/blob/e976a69408dcae86d20b33f29a96bd011e4a59ac/outputs/LSTM%20actual%20vs.png)

---


Team members&&their roles:
=========================
Salma Salah >>> LSTM && XGBoost

Mariam Abdel Fattah>>>
Marina Shnouda >>>
Shahd Mohamed Fouad>>>
Kareem Hamada >>>
