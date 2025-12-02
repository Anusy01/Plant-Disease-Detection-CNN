# Plant Disease Detection using CNN

## Description
This project implements a Convolutional Neural Network (CNN)–based system to
detect plant diseases from leaf images. The model predicts whether a plant is
healthy or affected by a specific disease along with prediction confidence
(e.g., Scab – 89%, Healthy – 100%).  
The system is designed to assist farmers and agricultural researchers in early
disease detection and crop health monitoring.

---

## Features
- Image-based plant disease classification
- CNN-based deep learning model
- Prediction with confidence score
- Simple Streamlit web interface
- Supports scalable and automated diagnosis

---

## Technology Stack
- Python
- TensorFlow / Keras
- CNN (Deep Learning)
- Streamlit
- NumPy, OpenCV

---

## Steps to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/Anusy01/Plant-Disease-Detection-CNN.git
cd Plant-Disease-Detection
pip install --upgrade pip
pip install -r requirements.txt

Download model.h5 from the link below and place it in the project folder:
https://drive.google.com/drive/folders/1siPKe3pmQdBkYxD42_8-qlL19Qh1XSHV

Run the application
streamlit run app.py

Output:
Predicts plant disease (e.g., Scab, Healthy)
Displays prediction confidence percentage