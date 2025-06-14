# 🔥 Forest Fire Detection Using Satellite Imagery

A deep learning-based web application built with **TensorFlow** and **Streamlit** to detect forest fires from satellite images. This model predicts whether a given satellite image contains signs of fire or not.

---

## 📸 Demo

Upload a satellite image, and the app will classify it as:
- **Fire 🔥**
- **No Fire**

---

## 🚀 Features

- User-friendly web interface via **Streamlit**
- Real-time predictions using a trained CNN model
- Simple drag-and-drop for image upload
- Visual confidence score

---

## 🧠 Model

- Trained using Keras/TensorFlow
- Model input size: `(64, 64, 3)`
- Output: Binary classification (`Fire`, `No Fire`)
- Model file: `Forest_fire_detection_model.h5`

---

## 🖥️ How to Run the App

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/forest-fire-detection.git
cd forest-fire-detection
