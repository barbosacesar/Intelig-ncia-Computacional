# Facial Emotion Analysis with LibreFace

This repository contains a facial emotion recognition interface powered by the `DeepFace` library and implemented in Python. It supports image uploads, ZIP batch analysis, and webcam capture directly in Google Colab. The system processes facial expressions and returns the dominant emotion with confidence metrics and visualizations.

---

## 🚀 Features

* Upload support for `.jpg`, `.png`, `.jpeg`, or `.zip` files containing images
* Webcam capture for real-time analysis (Google Colab only)
* Emotion prediction using pre-trained DeepFace backbones (VGG-Face, Facenet, OpenFace, etc.)
* Interactive HTML tables and bar chart visualizations
* Aggregated emotion statistics from multiple inputs (image batch or video frames)

---

## 📁 File Structure

```
/code/
├── analise_emocoes_imagem.ipynb        # Run image analysis (upload or webcam)
├── analise_emocoes_video.ipynb         # Run video (.avi) emotion frame analysis
├── funcoes_auxiliares.py               # Utilities for image processing and visualization

/assets/
├── exemplos/                           # Sample test images
├── graficos/                           # Saved charts and outputs
```

---

## 📦 Requirements

* Python 3.7+
* DeepFace
* OpenCV
* Pillow
* Matplotlib
* ipywidgets

Install dependencies:

```bash
pip install deepface opencv-python matplotlib ipywidgets pillow
```

> For webcam integration, we recommend running the notebook on [Google Colab](https://colab.research.google.com/).

---

## 🧠 Datasets Used

* [FER2013](https://www.kaggle.com/datasets/msambare/fer2013)
* [CK+ (Extended Cohn-Kanade)](http://www.jeffcohn.net/Resources/)
* [AffectNet](http://mohammadmahoor.com/affectnet/) *(license required)*

---

## 📊 Results

* Achieved **up to 85% accuracy** on basic emotion classification using VGG-Face
* Efficient performance in batch image and video analysis
* Visualizations with emoji labels, confidence bars, and frequency plots

---

## ▶️ How to Run

1. Launch `analise_emocoes_imagem.ipynb` on Google Colab
2. Run all cells to install and initialize
3. Upload an image, ZIP file, or capture a photo using the webcam
4. View processed results, charts, and emotion insights

---
