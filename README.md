# 🦴 MedImageNet: AI-powered Osteoporosis Detection from Knee X-rays

> Deep Learning-based multi-class classification of Knee X-ray images using a Convolutional Neural Network enhanced with Efficient Channel Attention (ECA).

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

Osteoporosis is a silent bone disease that often remains undiagnosed until fractures occur. Early detection plays a crucial role in preventing severe complications.

This project presents a deep learning-based approach for automatically classifying knee X-ray images into:

- 🟢 Normal
- 🟡 Osteopenia
- 🔴 Osteoporosis

The proposed architecture combines a Convolutional Neural Network (CNN) with **Efficient Channel Attention (ECA)** to improve feature representation while maintaining computational efficiency.

This work was developed as my undergraduate major project and later extended into a research publication.

---

## ✨ Features

- CNN with Efficient Channel Attention (ECA)
- Multi-class classification
- Medical image preprocessing
- Data augmentation using Albumentations
- Early stopping & model checkpointing
- Performance evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC-AUC
  - Confusion Matrix

---

# 🏗️ Model Pipeline

```text
Knee X-ray Images
        │
        ▼
Image Preprocessing
        │
        ▼
Data Augmentation
        │
        ▼
CNN + Efficient Channel Attention
        │
        ▼
Model Training
        │
        ▼
Prediction
        │
        ▼
Performance Evaluation
```

---

# 🛠 Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Albumentations
- Matplotlib
- Scikit-learn

---

# 📂 Dataset

**Dataset**

Multi-class Knee Osteoporosis X-ray Dataset

**Classes**

- Normal
- Osteopenia
- Osteoporosis

---

# 📊 Results

The proposed CNN + Efficient Channel Attention (ECA) model demonstrated strong performance in classifying knee X-ray images into three categories: **Normal**, **Osteopenia**, and **Osteoporosis**.

### Performance Evaluation

| Class | Precision | Recall | F1-Score | Support |
|-------|----------:|-------:|---------:|--------:|
| Normal | 90% | 81% | 85% | 635 |
| Osteopenia | 75% | 77% | 76% | 294 |
| Osteoporosis | 79% | 86% | 82% | 629 |
| **Macro Average** | **81%** | **81%** | **81%** | **1558** |
| **Weighted Average** | **83%** | **82%** | **82%** | **1558** |

### Overall Accuracy

**Accuracy:** **82.22%**


Evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve
- Confusion Matrix

---

# 📷 Sample Results

## Training Accuracy

> <img width="547" height="435" alt="image" src="https://github.com/user-attachments/assets/df917aae-ad7b-4b99-bcf4-6544052d40dc" />


```
images/training_accuracy.png
```

---

## ROC Curve

> <img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/2e9464cb-ff5f-49f8-8bdc-0180e31c3ce0" />


```
images/roc_curve.png
```

---

## Confusion Matrix

> <img width="665" height="545" alt="image" src="https://github.com/user-attachments/assets/ccb3be57-2c22-43df-a0ee-5202fc14b682" />


```
images/confusion_matrix.png
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/<your-username>/MedImageNet.git

cd MedImageNet
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

Open the notebook

```
notebooks/major-v.ipynb
```

Run all cells sequentially.

---

# 📁 Repository Structure

```
MedImageNet/

│── notebooks/
│     └── major-v.ipynb

│── images/
│     ├── training_accuracy.png
│     ├── confusion_matrix.png
│     └── roc_curve.png

│── checkpoints/

│── requirements.txt

│── README.md

│── LICENSE

│── .gitignore
```

---

# 📚 Research Publication

This project was extended into a research paper:

**Enhancing Osteoporosis and Osteopenia Diagnosis from Knee X-rays with Attention-Based Deep Learning**

Published/Accepted in:

**Journal of Information Systems Engineering and Management**

---

# 🔮 Future Work

Some possible future improvements include:

- FastAPI REST API
- Streamlit web application
- Grad-CAM explainability
- Docker deployment
- Clinical validation on larger datasets
- Model comparison with EfficientNet and Vision Transformers

---

# 👩‍💻 Author

**Ishika Thakur**

GitHub: https://github.com/ishika-thakur7802

LinkedIn: https://www.linkedin.com/in/ishika-thakur/

---

# 📜 License

This project is licensed under the MIT License.
