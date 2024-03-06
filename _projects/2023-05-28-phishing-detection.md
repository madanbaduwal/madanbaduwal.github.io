---
layout: page
title: Phishing Detection
description: 🕵️ Phishing detection using machine learning and URLs involves leveraging algorithms to analyze website URLs for signs of fraudulent activity.
img: assets/img/phishing-detection.jpg
importance: 8
category: project
---

Phishing attacks remain a significant security concern for both individuals and organizations, resulting in billions of dollars in losses annually. Machine learning (ML) has emerged as a promising approach for detecting such attacks by analyzing patterns and anomalies within large datasets. However, achieving an optimal balance between feature selection and model selection poses a challenging task in ML for phishing detection.

Traditional ML algorithms such as Logistic Regression (LR), Support Vector Machine (SVM), Random Forest (RF), XGBoost, and Naive Bayes (NB) often struggle with a low number of features, limiting their generalizability. Additionally, deep learning (DL) algorithms face difficulties in learning features from ambiguous behaviors between phishing and non-phishing websites.

This paper provides a comprehensive survey of various ML techniques and paradigms utilized for phishing website detection. It explores different datasets, features, and parameters within algorithms, along with the training time-space complexity involved in phishing detection. Furthermore, the survey compares the accuracies of different ML techniques.

The findings of this survey offer valuable insights into the current state of the art in phishing detection and can serve as a valuable resource for researchers and practitioners in the field.


<iframe width="700" height="500" src="https://www.youtube.com/embed/_Tv3nT6WqzU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>

# Run Project 

The Github repository can also be found here:

[![madanbaduwal/phishing-detection-transformer - GitHub](https://gh-card.dev/repos/madanbaduwal/phishing-detection-transformer.svg)](https://github.com/madanbaduwal/phishing-detection-transformer)
```bash

cd phishing-detection-transformer

cd src

pip3 install -r requirements.txt

streamlit run app.py

```