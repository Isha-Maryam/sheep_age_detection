# Sheep Age Detection Project

This project is a **Sheep Teeth Age Detection system** using **Deep Learning (CNN + Transfer Learning)**.  
The model classifies sheep teeth images into 4 classes and predicts their approximate age.

## Features

- Built with **TensorFlow / Keras**
- Uses **Transfer Learning** to improve performance on a small dataset
- Dataset augmented to improve accuracy
- Includes plots for **accuracy and sample images**
- Model saved in **Keras (.h5)** and **TF Lite (.tflite)** formats

## Folder Structure

- `notebook/` → Colab notebook with training, plots, and outputs
- `model/` → Saved models (`.h5` and `.tflite`)
- `images/` → Plots and sample images

## Training Results

- Final training **accuracy: 69-75%**  
- Accuracy plots are available in the `images/` folder  

## How to Use

1. Open the notebook in Colab or Jupyter to see training results.
2. Load the Keras model:
```python
from tensorflow.keras.models import load_model
model = load_model('model/sheep_age_model.h5')
