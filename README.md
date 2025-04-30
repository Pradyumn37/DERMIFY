# DERMIFY: Skin Disease Classification using Vision Transformer

DERMIFY is a deep learning project that leverages the Vision Transformer (ViT) architecture for accurate classification of skin diseases. Trained on the DermNet dataset, the model identifies 23 different skin conditions from over 20,000 high-resolution images.

---

## 🚀 Features

- ✅ Fine-tuned pretrained ViT model
- ✅ 23-class skin disease classification
- ✅ Trained on 20,000+ DermNet images
- ✅ Data augmentation and regularization
- ✅ Test-Time Augmentation (TTA) for improved inference
- ✅ High generalization and performance on medical images

---

## 🧠 Model Overview

Traditional CNNs extract local features hierarchically. In contrast, **ViT** treats images as sequences of patches and uses self-attention to capture long-range dependencies, making it well-suited for subtle pattern detection in medical images.

---

## 📁 Dataset

- **Source**: [DermNet](https://www.dermnet.com/)
- **Classes**: 23 skin diseases
- **Images**: ~20,000 total
- **Preprocessing**: Resized, normalized, and split into patches for ViT input

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/DERMIFY.git
cd DERMIFY
pip install -r requirements.txt
