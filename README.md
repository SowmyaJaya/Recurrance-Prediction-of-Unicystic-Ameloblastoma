# 🧠 Prediction of Recurrence of Unicystic Ameloblastoma using Deep Learning

> **Published in:** Digital Dentistry Journal (Elsevier), July 2025  
> **DOI:** [10.1016/j.ddj.2025.100029](https://doi.org/10.1016/j.ddj.2025.100029)  
> **Co-authors:** Sowmya K, Roopa S Rao, Divya BS, *et al.*

---

## 📌 Overview

This repository contains the implementation of a deep learning model, **ResCRAMNet**, developed to predict the recurrence of **Unicystic Ameloblastoma** using **Hematoxylin and Eosin (H&E)** stained whole slide images. The project is part of a **VGST SSR government-funded internship** in collaboration with the Faculty of Dental Sciences, MSRUAS.

---

## 🎯 Objective

- Develop an AI-based tool to assist in predicting the recurrence of odontogenic jaw tumors.
- Reduce diagnostic variability using attention-based deep learning.
- Enable early risk assessment to support personalized treatment planning in oral pathology.

---

## 🧪 Methodology

- **Dataset Preprocessing:**
  - Whole Slide Image tiling
  - Blank patch removal
  - Manual and semi-automated annotation of epithelial regions

- **Model Architecture:**
  - Backbone: `ResNet18`
  - Attention Layer: `CRAM (Cross-Resolution Attention Module)`
  - Classification Head: Fully connected layers with Softmax

- **Training & Evaluation:**
  - Optimizer: Adam
  - Loss Function: Categorical Crossentropy
  - Evaluation Metrics: Accuracy, Confusion Matrix, AUC

---

## 📊 Results

| Metric        | Value   |
|---------------|---------|
| Accuracy      | 92%     |
| AUC           | 0.95    |
| Recall (High Risk) | 91% |

---

## 🛠️ Tech Stack

- **Languages & Libraries:** Python, TensorFlow, Keras, OpenCV, NumPy, Pandas
- **Visualization:** Matplotlib, Seaborn
- **Histopathology Tools:** SlideViewer, ASAP
- **IDE:** Jupyter Notebook, VS Code

---

## 👩‍💻 My Role (Sowmya K)

- Data Curation and Image Preprocessing
- Model Architecture Design and Training
- Visualization and Result Interpretation
- Writing – Original Draft, Review & Editing
- Formal Analysis, Validation, and Methodology

---

## 📄 Citation

**Title:** *Prediction of Recurrence of Unicystic Ameloblastoma on H&E Whole Slide Images Using Deep Learning Techniques*  
**Journal:** Digital Dentistry Journal (Elsevier), 2025  
**DOI:** [10.1016/j.ddj.2025.100029](https://doi.org/10.1016/j.ddj.2025.100029)

