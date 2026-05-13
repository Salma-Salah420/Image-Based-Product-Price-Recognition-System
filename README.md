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




Team members&&their roles:
=========================
Salma Salah >>> Bert 

Mariam Abdel Fattah>>> DistillBert 

Marina Shnouda >>>  Effientnet 

Kareem Hamada >>> Resnet 

Shahd Mohamed>> Fusion Model&&Concatenate Results
