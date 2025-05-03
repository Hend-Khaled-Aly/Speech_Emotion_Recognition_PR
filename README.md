# **Speech_Emotion_Recognition_PR**

This project implements a Speech Emotion Recognition (SER) system using Convolutional Neural Networks (CNNs). The system converts speech signals into spectrograms and classifies them into emotional categories such as happiness, sadness, anger, fear, disgust, and neutral.

This project was completed as part of the **Pattern Recognition** course at the **Faculty of Engineering, Alexandria University**.

---

## 📌 Overview

Speech carries emotional information that can be decoded using signal processing and deep learning techniques. In this project, we extract features from audio samples and feed spectrogram representations into a custom CNN model to identify the emotion expressed in the voice.

The model is trained and evaluated using a stratified split and performance is analyzed using accuracy, F1-score, and confusion matrices.

---

## 📂 Contents

- **Jupyter Notebook** – Full code implementation including training, and evaluation  
- **Project Report** – Detailed explanation of the methodology with screenshots and evaluation metrices  
---

## ✨ Key Features

- Audio pre-processing using `librosa` (MFCC, pitch, ZCR, spectral centroid, etc.)
- Conversion of audio to spectrogram images
- Emotion label extraction and encoding
- Custom CNN model built with Keras and TensorFlow
- Evaluation with accuracy, precision, recall, and F1-score
- Confusion matrix and error analysis

---

## 🎧 Dataset

https://www.kaggle.com/dmitrybabko/speech-emotion-recognition-en

---

## 📎 Note

This repository contains the notebook and report only. For full details, refer to the included PDF report.
