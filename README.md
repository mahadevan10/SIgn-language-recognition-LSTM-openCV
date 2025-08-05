# 🧠 Action Detection with LSTM – Real-Time Human Pose Classification

> Real-time human action detection using LSTM on Mediapipe pose landmarks. Trained on 8 action classes with high accuracy and evaluated using multilabel confusion matrices. Model deployed for gesture recognition applications.

---

## 📌 Short Description

Real-time action detection using LSTM and Mediapipe pose landmarks. Trained on 8 classes with ~98% accuracy and validated using multilabel confusion matrix. Ideal for gesture and sign language recognition.

---

## Project Overview

This project implements a real-time action detection system using **LSTM neural networks**. It processes pose landmarks extracted using **Mediapipe** from webcam input and classifies them into one of **8 predefined gestures**.

---

## Model Architecture

```text
LSTM(64) → LSTM(128) → LSTM(64) → Dense(64) → Dense(32) → Dense(8)
```

## 🏗 Model Details

- **Loss Function**: `categorical_crossentropy`  
- **Optimizer**: `Adam` with learning rate 0.01  
- **Metrics**: Accuracy  
- **Epochs**: 80  
- **Parameters**: 203,624 total  

---

## 📊 Evaluation Results

- ✅ **Training Accuracy**: ~98.9%  
- ✅ **Validation Accuracy**: ~95%  
- ✅ **Metrics**: `multilabel_confusion_matrix` for per-class analysis  

**Example Confusion Matrix Output:**

[[61, 0],
[ 0,11]]

[[62, 1],
[ 1, 8]]



---

## 🛠 Tech Stack

- Python  
- TensorFlow / Keras  
- Mediapipe  
- NumPy  
- OpenCV  
- Jupyter Notebook  

---

## 🎥 Demo

📽️ Real-time webcam gesture recognition  
▶️ `Recording 2025-08-05 112324.mp4`

---

## 📁 Files Included

- `Action Detection Refined.ipynb` – Full code  
- `model.h5` – Trained model  
- `README.md` – This file  
- `.mp4` – Sample prediction recording
- `image` – Model Summary
- `image` – Confusion Matrix


---

## 🧪 How to Run

```bash
git clone https://github.com/yourusername/action-detection-lstm.git
cd action-detection-lstm
jupyter notebook


