# 🖼️ Text-to-Image Generation using Attention-Based GANs

## 📌 Project Overview

This project implements a **Text-to-Image Generative Adversarial Network (GAN)** enhanced with **Self-Attention and Cross-Attention mechanisms** to generate high-quality images from textual descriptions.

By incorporating attention, the model learns to focus on **important words in the input text** and **relevant regions in the image**, resulting in sharper images and better text–image alignment.

---

## 🎯 Problem Statement

Traditional GAN-based text-to-image models often struggle to align complex textual descriptions with generated images.  
This project aims to solve that by integrating **attention mechanisms** so the model can:

- Understand which words matter most
- Capture long-range dependencies in images
- Improve semantic consistency between text and image

---

## 🚀 Key Features

- ✅ GAN-based text-to-image generation
- ✅ **Self-Attention** for image feature refinement
- ✅ **Cross-Attention** for text–image alignment
- ✅ Clean, modular PyTorch implementation
- ✅ End-to-end pipeline: EDA → Training → Evaluation

---

## 🛠️ Tools & Technologies

- **Python**
- **PyTorch**
- **Jupyter Notebook / Google Colab**
- **Pandas, NumPy**
- **Matplotlib / Seaborn**
- **Scikit-learn (basic utilities)**
- **Git & GitHub**

---

## 📂 Dataset

### Dataset Used
**CUB-200-2011 (Birds Dataset)**  
- Bird images with multiple human-written captions  
- Well-suited for fine-grained text-to-image tasks  

📌 *Alternative:* MS-COCO dataset (not included)

### Preprocessing Steps
- Resize images to `64 × 64`
- Normalize pixel values to `[-1, 1]`
- Tokenize and pad text captions
- Create text embeddings

---

## 🧠 Model Architecture
