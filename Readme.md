# Traffic Sign Classification – COMP30027 Project 2 (2025)

## Project Overview
This project focuses on classifying **German traffic signs** into one of **43 classes** using image features. The goal is to demonstrate **feature extraction, preprocessing, and machine learning** workflows for multi-class image classification.

---

## Data
- **Training images:** 5,488 (with labels)  
- **Test images:** 2,353 (without labels)  
- **Classes:** 43 traffic sign types  

### Features Provided
- **HOG (Histogram of Oriented Gradients)** — PCA-reduced  
- **Color histograms**  
- **Additional features** — edge density, texture variance, mean RGB  

---

## Methods
1. **Data preprocessing** – normalization, feature selection  
2. **Modeling** – trained and tuned classifiers including:
   - Support Vector Machines (SVM)
   - Random Forest
   - Logistic Regression  
3. **Stacking ensemble** – combined predictions from base models for improved accuracy  
4. **Evaluation** – measured performance using accuracy and per-class F1 scores  

---

## Skills & Tools
- **Languages:** Python  
- **Libraries:** scikit-learn, numpy, pandas, matplotlib  
- **Techniques:** Feature engineering, PCA, machine learning, ensemble modeling, evaluation metrics  

---

> Note: This project was completed as part of the COMP30027 course at the University of Melbourne. Code and analysis have been adapted for portfolio presentation.
