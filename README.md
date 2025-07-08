# Alzheimer-s-Disease-Prediction
# 🧠 Alzheimer's Disease Prediction Using CNN, DenseNet-50 & ResNet-50

This project aims to classify different stages of **Alzheimer's Disease** using **MRI brain images**. Leveraging deep learning models — **Custom CNN**, **DenseNet-50**, and **ResNet-50**, the system accurately detects the disease in its various stages to assist with early diagnosis and treatment planning.

---

## 🗂️ Dataset

- Publicly available **Alzheimer's MRI Dataset**
- Four classification categories:
  - `NonDemented`
  - `VeryMildDemented`
  - `MildDemented`
  - `ModerateDemented`
- Includes T1-weighted MRI images of the brain
- Preprocessed using resizing, normalization, and augmentation techniques

---

## ⚙️ Technologies Used

- **Python**
- **TensorFlow / Keras**
- **NumPy**, **Matplotlib**
- **Sklearn**
- **Transfer Learning**

---

## 🧠 Models Used

### 1. 🔧 Custom CNN
- 3 convolutional layers
- Max pooling, dropout, dense layers
- Baseline accuracy ~90%

### 2. ⚙️ DenseNet-50 (Transfer Learning)
- Fine-tuned top layers
- Dense connections improve gradient flow
- Highest accuracy: **94.3%**

### 3. 🔁 ResNet-50 (Transfer Learning)
- Residual blocks handle deeper learning
- Accuracy: **92.7%**

---

## 📈 Results

| Model        | Accuracy | Comments                             |
|--------------|----------|--------------------------------------|
| CNN          | 90.1%    | Fast and lightweight                 |
| DenseNet-50  | 94.3%    | Best accuracy, low overfitting       |
| ResNet-50    | 92.7%    | Stable, effective for deep learning  |

- Evaluated using **accuracy**, **precision**, **recall**, **F1-score**, and **confusion matrix**
- **Stratified K-Fold Cross Validation** used for robust evaluation

---
