# 🧬 GLEASON AI — HybridKAN

### Automatic Gleason Score Classification from Prostate Histopathological Images

<p align="center">
  <b>A Deep Learning Approach for Prostate Cancer Histopathological Image Classification</b>
</p>

---

## 📌 Overview

**GLEASON AI** is a medical artificial intelligence research project focused on the automatic classification of prostate histopathological images according to Gleason grading.

The project explores a hybrid deep learning architecture called **HybridKAN**, combining Convolutional Neural Networks (CNNs) with Kolmogorov-Arnold Networks (KANs), aiming to investigate an alternative approach to histopathological image classification.

The objective is to support the analysis of prostate tissue images and explore the potential of AI-assisted pathological assessment.

> This project is developed for academic and research purposes and is not intended to replace professional medical diagnosis.

---

## 🎯 Objectives

- Develop an automatic classification system for prostate histopathological images.
- Explore the integration of CNN feature extraction and KAN-based classification.
- Evaluate the performance of different deep learning architectures.
- Compare the proposed HybridKAN approach with baseline models.
- Investigate AI-assisted solutions for medical image analysis.

---

## 🧠 Proposed Approach: HybridKAN

The proposed architecture combines:

- **CNN:** Extracts spatial and morphological features from histopathological images.
- **KAN:** Learns nonlinear relationships between extracted features.
- **Hybrid Classification:** Integrates both components for image classification.

### Architecture Pipeline

```text
Histopathological Image
          ↓
    CNN Feature Extraction
          ↓
     Feature Representation
          ↓
      KAN Classifier
          ↓
   Gleason Classification
```

---

## 🗂️ Dataset

**Dataset:** Prostate Gleason Dataset

The dataset contains approximately 65,041 histopathological images organized into four classification categories.

| Class | Description |
|---|---|
| 0 | Benign / Healthy Tissue |
| 1 | Gleason Grade 3 (G3) |
| 2 | Gleason Grade 4 (G4) |
| 3 | Gleason Grade 5 (G5) |

### Data Preparation

- Stratified dataset splitting
- Training: 70%
- Validation: 15%
- Testing: 15%

The dataset is organized to maintain class distribution across subsets and avoid information leakage between training and evaluation.

---

## ⚙️ Methodology

The project follows these main stages:

1. Dataset exploration and visualization.
2. Image preprocessing and data preparation.
3. Deep learning model implementation.
4. Model training and validation.
5. Performance evaluation.
6. Comparative analysis of architectures.
7. Development of a prototype interface.

---

## 📊 Experimental Evaluation

Several deep learning architectures are considered for comparative evaluation.

| Model | Architecture |
|---|---|
| DenseNet121 | CNN |
| ResNet | CNN |
| EfficientNet | CNN |
| HybridKAN | CNN + KAN |

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Training and Validation Loss

*Final experimental results will be documented after completing the evaluation process.*

---

## 🖥️ Technologies

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- Git & GitHub

---

## 📁 Repository Structure

```text
GLEASON-AI-HybridKAN/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   ├── data_exploration.ipynb
│   ├── densenet121.ipynb
│   └── hybridkan.ipynb
│
├── src/
│   ├── models/
│   ├── training/
│   ├── evaluation/
│   └── preprocessing/
│
├── results/
│   ├── figures/
│   └── metrics/
│
├── figures/
│   ├── architecture.png
│   └── methodology.png
│
└── demo/
    └── screenshots/
```

---

## 🚀 Future Perspectives

- Further optimization of the HybridKAN architecture.
- Extended experiments and model comparisons.
- Improved classification performance and generalization.
- Development of an interactive AI-assisted classification prototype.
- Exploration of explainability techniques for medical image analysis.

---

## 👩‍💻 Authors

**Khettab Meryem**  
**Mahmoudi Wissal Meriem**

Master's Degree — Information Systems & Web Intelligence (ISI & WIC)

Université Djillali Liabès de Sidi Bel Abbès  
Academic Year: 2025–2026

### Supervisors

- Dr. BERRABAH Djamel
- Dr. BOUSMAHA Rabab

---

## 📄 Academic Context

This project was developed as part of a Master's graduation thesis in Artificial Intelligence and Medical Image Analysis.

---

## ⚖️ Disclaimer

GLEASON AI is an academic research project. Its predictions are experimental and must not be used as a substitute for clinical diagnosis or professional medical judgment.
