# ✍️ Draw a Digit – Handwritten Digit Recognition App

This is a simple web app that lets you **draw a digit (0–9)** and uses **machine learning (TensorFlow.js)** to predict what number you drew.

---

## 🚀 Features

- 🖍️ Draw digits directly in your browser
- 🧠 ML-powered prediction using a pre-trained MNIST model
- 👆 Supports both mouse and touch input
- ⚡ Works fully client-side — no backend required

---

## 🛠 Technologies Used

- HTML / CSS / JavaScript
- TensorFlow.js
- Pre-trained MNIST model

---

## 📦 How to Use

1. Clone or download the repository
2. Open `index.html` in your browser
3. Draw a digit (0–9) in the canvas
4. Click **"Process"** to get the predicted result
5. Click **"Clear"** to reset the canvas

---

## 🧠 Model Details

- The model is hosted [here](https://github.com/Mabaka/mnst)
- Loaded directly via URL using `tf.loadLayersModel`
- Based on the MNIST dataset for digit recognition

