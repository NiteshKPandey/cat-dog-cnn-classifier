# cat-dog-cnn-classifier
CNN-based image classifier with confidence scoring

# 🐶🐱 Cat vs Dog Image Classifier (CNN)

A deep learning project that classifies images as **Cat 🐱 or Dog 🐶** using a Convolutional Neural Network (CNN), with confidence scoring and visual prediction output.

---

## 🚀 Project Overview

This project demonstrates a complete deep learning workflow:

* Data preprocessing using image generators
* CNN model training using TensorFlow/Keras
* Image classification with confidence scoring
* Model evaluation and visualization

---

## 🧠 Model Details

* Architecture: Custom CNN
* Input size: 128 × 128 × 3
* Output: Binary classification (Cat / Dog)
* Activation: Sigmoid
* Loss function: Binary Crossentropy
* Optimizer: Adam

---

## 📊 Features

* ✅ Image classification (Cat vs Dog)
* ✅ Confidence score output
* ✅ Data preprocessing pipeline
* ✅ Training and validation tracking
* 🔜 Grad-CAM heatmap visualization (planned)
* 🔜 Web app deployment using Streamlit

---

## 📁 Project Structure

```
cat-dog-cnn-classifier/
│
├── notebook.ipynb
├── README.md
```

---

## 🖼️ Example Output

```
Prediction: Dog 🐶
Confidence: 87.23%
```

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```
git clone https://github.com/NiteshKPandey/cat-dog-cnn-classifier.git
cd cat-dog-cnn-classifier
```

### 2. Install dependencies

```
pip install tensorflow numpy matplotlib pillow
```

---

## 📦 Model File

Due to GitHub size limitations, the trained model is not included in this repository.

👉 Download model from:
(Add your Google Drive link here)

---

## ▶️ Run Prediction (Example)

```python
from tensorflow.keras.models import load_model
model = load_model("cnn_model.keras")
```

---

## 📌 Future Improvements

* Add Grad-CAM visualization
* Upgrade model using transfer learning (MobileNet / ResNet)
* Deploy as web application (Streamlit)
* Extend to multi-class classification

---

## 💡 Key Learnings

* Understanding CNN architecture
* Image preprocessing pipelines
* Model training and evaluation
* Real-world ML workflow

---

## 📬 Author

Your Name
https://github.com/NiteshKPandey

---
