# 🫁 Tuberculosis (TB) Detection using Deep Learning

This project implements a **Convolutional Neural Network (CNN)** for detecting **Tuberculosis (TB)** from chest X-ray images.  
It uses the publicly available **[Tuberculosis Chest X-ray Dataset](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset)** and achieves high accuracy on unseen test data.

---

## 📌 Features
- Preprocessing of chest X-ray dataset (4200 images: 3500 Normal, 700 TB)  
- Stratified Train/Validation/Test split  
- On-the-fly image augmentation (flip, rotation, zoom)  
- Class weights to handle imbalance  
- CNN model with Conv2D, MaxPooling, Dense, Dropout  
- Training with **EarlyStopping** and **ReduceLROnPlateau**  
- Evaluation: Accuracy, AUC, Precision, Recall, F1-score  
- Visualizations: Training curves, Confusion Matrix, Precision-Recall curve  

---
