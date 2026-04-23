# 🚀 Real-Time Motion Detection using OpenCV

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
</p>

---

## 📌 Overview
This project implements a **real-time motion detection system** using computer vision techniques.  
It detects moving objects in video streams and highlights them using bounding boxes.

---

## ⚡ Demo (Real Output)

<p align="center">
  <img src="demo.gif" width="700">
</p>

<p align="center">
  🎯 Real-time motion detection with bounding boxes
</p>

---

## 🧠 How It Works

The system follows a simple but effective pipeline:

1. Capture consecutive frames from video  
2. Compute the difference between frames  
3. Convert to grayscale  
4. Apply Gaussian blur (reduce noise)  
5. Apply thresholding  
6. Detect contours (moving objects)  
7. Draw bounding boxes around motion  

---

## 🛠️ Tech Stack

- 🐍 Python  
- 👁️ OpenCV  
- 🔢 NumPy  

---

## ▶️ How to Run

```bash
pip install opencv-python numpy
python untitled1.py
