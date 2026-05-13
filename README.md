 Image-Based-Product-Price-Recognition-System
=================================================

<img src="https://github.com/Salma-Salah420/Image-Based-Product-Price-Recognition-System/blob/4029ec771f66e8f3df6c37861d8ebc684d6ee519/images/OIP.webp" width="600"/>

Problem Definition:
========================
Given a product name as a query, we need to retrieve the top‑K most similar products from a product catalog.
Similarity is measured in the embedding space using cosine similarity.
========

Challenges:-
==============

Product names may be short, ambiguous, or contain typos.

Different products may have similar names but different meanings (e.g., "iPhone 13" vs "iPhone 13 case").

Need to choose an embedding model that captures semantic not just lexical similarity.

Product Detection: Identify products in images using computer vision algorithms.

Price Recognition: Detect and read price tags from product images.

Multiple Products Handling: Works with images containing several products at once.

Data Export: Save extracted product names and prices in structured formats like CSV or JSON.

Cross-Platform: Works with images captured by mobile phones, cameras, or online sources.

Use Cases:
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

  2. Using BERT  Before Fine-Tuning :
  ![loss](https://github.com/Salma-Salah420/Image-Based-Product-Price-Recognition-System/blob/2088ba6e2ed7506ad5641b93a18fbe29d69dc4bf/images/download%20(1).png)

--our confusion Matrix after fine_tuning:
![loss](https://github.com/Salma-Salah420/Image-Based-Product-Price-Recognition-System/blob/7e863b27eb8e705ccf606defb74dc5dd1bb81386/images/download%20(2).png)

---


Team members&&their roles:
=========================
Salma Salah >>> Bert 

Mariam Abdel Fattah>>> DistillBert 

Marina Shnouda >>>  Effientnet 

Kareem Hamada >>> Resnet 

Shahd Mohamed>> Fusion Model&&Concatenate Results
