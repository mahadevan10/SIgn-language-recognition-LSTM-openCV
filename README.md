# 🧠 Action Detection with LSTM – Real-Time Human Pose Classification

> Real-time human action detection using LSTM on Mediapipe pose landmarks. Trained on 8 action classes with high accuracy and evaluated using multilabel confusion matrices. Model deployed for gesture recognition applications.

---

## 📌 Short Description (≤ 350 characters)

Real-time action detection using LSTM and Mediapipe pose landmarks. Trained on 8 classes with ~98% accuracy and validated using multilabel confusion matrix. Ideal for gesture and sign language recognition.

---

## 🚀 Project Overview

This project implements a real-time action detection system using **LSTM neural networks**. It processes pose landmarks extracted using **Mediapipe** from webcam input and classifies them into one of **8 predefined gestures**.

---

## 🏗 Model Architecture

```text
LSTM(64) → LSTM(128) → LSTM(64) → Dense(64) → Dense(32) → Dense(8)
Loss Function: categorical_crossentropy

Optimizer: Adam 

Metrics: Accuracy

Epochs: 80

Parameters: 203,624 total

'''
