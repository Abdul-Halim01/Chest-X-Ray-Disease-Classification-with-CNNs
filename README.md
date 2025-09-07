# 🩺 Chest X-Ray Disease Classification with CNNs

This repository contains experiments on **Chest X-Ray image classification** using different **Convolutional Neural Network (CNN)** architectures.  
The goal is to evaluate custom and pre-trained deep learning models on medical imaging tasks and compare their performance.

---

## 📂 Repository Structure

- **`chest_dis_classification.ipynb`**  
  - Implements:
    - Custom CNN (built from scratch)  
    - MobileNetV2 (transfer learning)  
    - ResNet50V2 (transfer learning)  
- **`DenseNet.ipynb`**  
  - Implements:
    - DenseNet-121 (transfer learning)

---

## 📊 Results Summary

| Model          | Type             | Accuracy |
|----------------|------------------|----------|
| Custom CNN     | From scratch     | **86%**  |
| MobileNetV2    | Pre-trained (TL) | **96%**  |
| ResNet50V2     | Pre-trained (TL) | **98%**  |
| DenseNet-121   | Pre-trained (TL) | **89%**  |

---

## ⚙️ Features
- Data preprocessing & augmentation using `ImageDataGenerator`  
- Training pipelines with early stopping & learning rate scheduling  
- Evaluation with accuracy, precision, recall, F1-score, and confusion matrix  
- Visualization of learning curves and predictions  

---

## 🎯  Goal

- To explore how different CNN architectures (both custom and transfer learning) perform on chest disease classification and identify the most effective approaches.
