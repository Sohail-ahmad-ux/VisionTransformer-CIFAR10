# 🧠 Vision Transformer (ViT) on CIFAR-10

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)

**A clean and efficient Vision Transformer implementation from scratch for CIFAR-10 image classification.**

---

## ✨ Features

- ✅ **Pure PyTorch** implementation (no external ViT libraries)
- ✅ Patch embedding + CLS token + Positional embeddings
- ✅ Transformer Encoder with multi-head attention
- ✅ GPU acceleration support (CUDA)
- ✅ Training pipeline with AdamW optimizer
- ✅ Real-time evaluation & prediction examples
- ✅ Modular and well-documented code

---
## 🧪 Model Architecture

Image Size: 32×32 (CIFAR-10)
Patch Size: 4×4
Embedding Dimension: 128
Depth (Layers): 4
Attention Heads: 4
MLP Head: Linear classifier

## 📸 Sample Predictions

# Example outputs from the model:
Actual: cat        | Predicted: frog
Actual: ship       | Predicted: ship      ✓
Actual: automobile | Predicted: automobile ✓

## 📊 Results

| Metric              | Value     |
|---------------------|-----------|
| **Test Accuracy**   | **27.67%** |
| Epochs Trained      | 20        |
| Batch Size          | 128       |
| Learning Rate       | 1e-3      |

> *Note: This is a lightweight baseline model. Further improvements in depth, embedding size, data augmentation, and longer training can significantly boost performance.*

---

## 🛠️ Technologies Used

- **PyTorch** (Deep Learning Framework)
- **Torchvision** (Datasets & Transforms)
- **CUDA** (GPU Acceleration)
- **Python 3.12**

---

## 📁 Project Structure

```bash
Vision-Transformer-CIFAR10/
├── visiontransformer2.ipynb    # Main Jupyter Notebook
├── README.md
└── data/                       # Auto-downloaded by torchvision
