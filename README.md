
![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

# Sheep Age Detection Project 🐑

This project is a **Sheep Teeth Age Detection System** built using **Deep Learning (CNN + Transfer Learning)**.  
The model predicts the **approximate age of a sheep** based on an image of its teeth.

This project was developed as part of my deep learning practice and is intended for **educational and research purposes**.

---

## 📱 Mobile App (Download & Test)

The trained Sheep Age Detection model is integrated into a mobile application where users can upload a sheep teeth image and get the predicted age instantly.

🔽 **Download the App From Here:**  
👉[![Download App](https://img.shields.io/badge/Download-App-blue?style=for-the-badge&logo=android)](https://github.com/Isha-Maryam/sheep_age_detection/releases/download/Sheep-Age-Detector/app-release.apk)

### 🔧 App Features:
- Upload sheep teeth image
- Real-time age prediction
- Uses trained CNN model
- Lightweight and easy to use
- Offline prediction (TF Lite)

### 👨‍💻 App Developed By:
**Ziauddin Developer**   
📌Get in Touch with Team : **ziauddindeveloper@gmail.com**  and  **ishamaryam69@gmail.com**

---

## 🔍 Problem Statement

Determining the age of livestock manually is time-consuming and requires expertise for
checking qurbani eligibility. 
This project automates the process using computer vision by analyzing sheep teeth images.

---

## 🚀 Features
- Yolov8 used for Sheep Integrity Check.
- Deep Learning-based image classification  for analyzing teeth patterns.
- Herd Management System for managing sheeps sales, expenses & health related tasks.
- Transfer Learning for better performance on small datasets  
- Data augmentation to improve generalization  
- Supports multiple age classes  
- Model exported to **Keras (.h5)** and **TensorFlow Lite (.tflite)**  
- Visualization of accuracy, loss, and sample predictions  
- Model implemented in app as well

---

## 🧠 Model & Approach

- Framework: **TensorFlow / Keras**
- Architecture:
  - Pretrained CNN model (Transfer Learning)
  - Global Average Pooling
  - Fully connected layers
- Dataset:
  - 4 classes
  - ~50–60 images per class
  - Data augmentation applied

---

## 📁 Folder Structure

```

sheep-age-detection/
│
├── notebook/        # Training notebook (.ipynb)
├── model/           # Saved models (.h5, .tflite)
├── images/          # Accuracy,loss & dataset sample images
└── README.md

````

---

## 📊 Training Results

- **Final Accuracy:** ~80%
- Accuracy and loss graphs are available in the `images/` folder
- Sample predictions visualized during training

---

## ▶️ How to Use

### Load Keras Model
```python
from tensorflow.keras.models import load_model

model = load_model('model/sheep_age_model.h5')
````

### Load TensorFlow Lite Model

```python
import tensorflow as tf

interpreter = tf.lite.Interpreter(
    model_path="model/sheep_age_model.tflite"
)
interpreter.allocate_tensors()
```

---

## 📌 Notes

* Dataset size was limited, so accuracy may vary
* Data augmentation was used to improve performance
* TF Lite version is suitable for mobile deployment


---

## 👩‍💻 Author

**Isha Maryam**
Undergraduate Computer Science | AI & Deep Learning Enthusiast

🔗 GitHub: [https://github.com/Isha-Maryam](https://github.com/Isha-Maryam)
🔗 Portfolio:[https://isha-maryam-ai-engineer.web.app/](https://isha-maryam-ai-engineer.web.app/)
🔗 LinkedIn: [https://www.linkedin.com/in/isha-maryam-84ab8a327/](https://www.linkedin.com/in/isha-maryam-84ab8a327/)




