# KID-VLM: Multimodal Toxic Meme Detection using Vision-Language Models

<p align="center">
  <b>Undergraduate Research Project | Aug 2025 – Dec 2025</b>
</p>

<p align="center">
Multimodal Deep Learning • Computer Vision • NLP • Vision-Language Models • Hate Speech Detection
</p>

---

## 📌 Overview

The rapid growth of social media has increased the spread of **toxic and hateful memes**, where offensive meaning often emerges only when **both the image and accompanying text** are interpreted together.

Traditional text-only or image-only models fail to capture this multimodal context effectively. This research explores multiple machine learning and deep learning techniques for multimodal meme understanding and proposes **KID-VLM (Knowledge-Infused Distilled Vision-Language Model)** for hate speech detection.

The project presents a comparative study of classical ML models, transformer-based NLP models, computer vision architectures, and multimodal learning techniques.

---

## 🎯 Objectives

- Detect hateful memes using both textual and visual information.
- Compare traditional ML, deep learning, and multimodal approaches.
- Evaluate Vision-Language Models for multimodal understanding.
- Design an efficient multimodal fusion framework.
- Improve classification performance using knowledge distillation.

---

## 📂 Dataset

### Facebook Hateful Memes Dataset

- **8,500+ labeled memes**
- Binary Classification
  - Hateful
  - Non-Hateful

Additional experiments were conducted using the **HarMeme Dataset**.

---

## 🧠 Models Evaluated

### Text Models
- TF-IDF + SVM
- Fine-tuned BERT

### Image Models
- ResNet50
- Vision Transformer (ViT)

### Vision-Language Models
- CLIP

### Proposed Framework
- **KID-VLM**

---

## ⚙️ Methodology

The proposed workflow combines textual and visual representations into a unified multimodal learning pipeline.

```
                Image
                  │
        Image Feature Extractor
                  │
                  ├──────────────┐
                  │              │
                  │        Multimodal Fusion
                  │              │
Text ─────► Text Encoder         │
                  │              │
                  └──────────────┘
                         │
                Classification Head
                         │
                  Hateful / Non-Hateful
```

The proposed KID-VLM framework combines:

- Text embeddings
- Visual embeddings
- Knowledge representations
- Multimodal feature fusion
- Knowledge Distillation

---

## 🛠️ Tech Stack

| Category | Technologies |
|-----------|--------------|
| Programming | Python |
| Deep Learning | PyTorch |
| NLP | BERT |
| Computer Vision | ResNet50, Vision Transformer (ViT) |
| Vision-Language Models | CLIP |
| Machine Learning | TF-IDF, SVM |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib |

---

## 📊 Experimental Results

| Model | Accuracy | AUC |
|--------|---------:|----:|
| TF-IDF + SVM | 57.20% | 0.59 |
| ResNet50 | 62.10% | 0.65 |
| Vision Transformer | 65.30% | 0.69 |
| CLIP | 68.80% | 0.72 |
| **Fine-tuned BERT** | **81.25%** | **0.87** |
| **KID-VLM** | **77.00%** | **0.82** |

---

## 🚀 Key Contributions

- Conducted comparative evaluation of **10+ text, image, and multimodal models** for toxic meme detection.
- Implemented transformer-based and vision-based approaches including **BERT, CLIP, ViT, ResNet50, TF-IDF, and SVM**.
- Designed and evaluated the proposed **KID-VLM** multimodal framework using knowledge distillation and multimodal fusion.
- Performed extensive experimentation, model benchmarking, and performance analysis.
- Co-authored the research manuscript documenting methodology, experiments, and findings.

---

## 📈 Future Work

- Large Vision-Language Models (LVLMs)
- Explainable AI for Multimodal Models
- Knowledge Graph Integration
- Multilingual Meme Detection
- Real-time Content Moderation
- Edge Deployment

---

## 📄 Research Paper

The complete research manuscript is available in:

```
paper/KID-VLM_Research_Paper.pdf
```
---

## 📜 License

This repository is intended solely for **academic and research purposes**.

---

## 👩‍💻 Author

**Harshita Tiwari**

---
⭐ If you found this repository interesting, consider giving it a star!
