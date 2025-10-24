# 🧠 Brain Tumor Detection using Deep Learning and Machine Learning

Detection of Brain Tumor from MRI images through Deep Learning and classification of tumor types.

---

## 📘 Overview

This project implements a complete pipeline for **brain tumor detection from MRI images**, inspired by the research paper:  
**"MRI Brain Tumor Detection using Deep Learning and Machine Learning Approaches" (Anantharajan et al., 2024).**

The system classifies MRI images into **four categories**:
- 🧩 **Glioma**
- 🧠 **Meningioma**
- 🧍 **Pituitary Tumor**
- ✅ **No Tumor**

The pipeline includes **preprocessing, segmentation, feature extraction, and hybrid classification** using CNN and SVM.

---

## ✨ Features

- 🔹 **CLAHE** – Improves MRI image contrast adaptively.  
- 🔹 **Fuzzy C-Means (FCM)** – Segments the tumor region effectively.  
- 🔹 **GLCM Features** – Extracts texture-based statistical features.  
- 🔹 **CNN-based Deep Features** – Learns high-level image features.  
- 🔹 **EDN-SVM Classifier** – Combines deep + texture features using a Support Vector Machine.

---

## 🧰 Tech Stack

| Category | Tools/Libraries |
|-----------|----------------|
| Deep Learning | TensorFlow, Keras |
| Machine Learning | Scikit-learn |
| Image Processing | OpenCV, Scikit-image, fcmeans |
| Visualization | Matplotlib, Seaborn |
| Utilities | NumPy, tqdm |

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/BrainTumorDetection.git
   cd BrainTumorDetection

## README — How to run locally

1. Install backend dependencies (recommended inside a venv):

```bash
cd backend
python -m venv venv
source venv/bin/activate # on windows: venv\Scripts\activate
pip install flask pillow numpy
python app.py
```

2. Install frontend and run

```bash
cd frontend # where package.json is
npm install
npm start
```

