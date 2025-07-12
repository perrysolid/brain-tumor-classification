# 🧠 Brain Tumor Classification Using VGG16

This project implements a deep learning-based image classification model to detect and classify brain tumors using MRI scans. It leverages a pre-trained VGG16 model with fine-tuning and transfer learning to accurately classify MRI images into the following tumor categories:

- **Glioma**
- **Meningioma**
- **Pituitary Tumor**
- **No Tumor**

---

## 📁 Dataset

The dataset is sourced from [Kaggle - Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)).

## 🧪 Model

- Model: `VGG16` (Transfer Learning)
- Optimizer: `Adam`
- Loss: `categorical_crossentropy`
- Metrics: `accuracy`
- Input size: `224x224`
- Batch size: `32`

## 📊 Results

- **Training Accuracy**: ~99%
- **Validation Accuracy**: ~96%

### 🧮 Confusion Matrix Insight

- ✅ High overall **precision** and **recall** across all classes
- ⚠️ A few misclassifications observed between **pituitary** and **glioma** tumor classes


