# Klasifikasi-Gambar-Beras

This project is a Convolutional Neural Network (CNN) based image classification system to identify different types of rice grains using TensorFlow. The trained model is exported in multiple formats for different deployment scenarios including:

- ✅ TensorFlow SavedModel (for TF Serving / retraining)
- ✅ TensorFlow Lite (.tflite for mobile and embedded)
- ✅ TensorFlow.js (for in-browser prediction)

---

## 📂 Project Structure

---

## 🏷️ Classes

The model was trained to recognize the following 5 classes of rice:

- Arborio
- Basmati
- Ipsala
- Jasmine
- Karacadag

---

## 🚀 Model Training

The CNN architecture consists of:

- Conv2D layers
- MaxPooling layers
- Dense and Dropout layers

Training was performed using `ImageDataGenerator` with validation split for efficiency and memory optimization.

---

## 📦 Requirements

To install dependencies:

---

## 🧪 Deployment Options

- **TFLite**: Use `tflite/model.tflite` for deployment in mobile apps.
- **TFJS**: Use `tfjs_model/model.json` with `TensorFlow.js` for browser-based predictions.
- **SavedModel**: Use `saved_model/` for TensorFlow Serving or further model refinement.

---

## 🙋 Author

Developed by Putu Gio Satria Adinata
Dicoding
Date: May 2025

