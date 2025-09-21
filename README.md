# 🩺 Skin Disease Classification using Deep Learning (CNN)

## 📌 Overview
This project focuses on building a **deep learning model** to classify **skin diseases** from medical images. Using **Convolutional Neural Networks (CNNs)**, the model learns to differentiate between **healthy and diseased skin**, enabling early diagnosis and AI-powered healthcare support.

---

## 🎯 Objectives
- Automate skin disease detection from medical images  
- Improve diagnostic accuracy compared to manual inspection  
- Provide scalable AI solutions for healthcare  

---

## 📂 Dataset
- Publicly available **Skin Disease Image Dataset**  
- Split into **Training, Validation, and Test sets**  
- Preprocessing applied:
  - Resizing images  
  - Normalization  
  - Data Augmentation (rotation, flip, zoom)  

---

## 🔑 Key Steps
### 1. Data Preparation
- Imported dataset and performed preprocessing  
- Partitioned into train/validation/test  

### 2. Model Development
- Built a **CNN architecture** with multiple convolution + pooling layers  
- Optimizer: **Adam**  
- Loss: **SparseCategoricalCrossentropy**  
- Used data augmentation to reduce overfitting  

### 3. Training & Evaluation
- Trained for multiple epochs with batch optimization  
- Evaluated accuracy & loss on unseen test data  
- Achieved **high accuracy in classifying skin diseases**  

### 4. Results & Insights
- Plotted **accuracy/loss curves**  
- High **Test Accuracy** achieved  
- Model saved for deployment and further integration  

---

## 📊 Results
- **Training Accuracy**: 96.27%  
- **Validation Accuracy**: 98.43%  
- **Test Accuracy**: 96.88%  
