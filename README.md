# Plant Disease Detection Using CNN-Based Image Classification

## Project Overview

This project uses Deep Learning and Computer Vision techniques to detect plant diseases from leaf images. The model is built using a Convolutional Neural Network (CNN) with MobileNetV2 transfer learning and is capable of classifying multiple plant diseases as well as healthy leaves.

The system can assist farmers and agricultural professionals in early disease detection, helping improve crop health and productivity.

---

## Features

* Plant disease classification from leaf images
* Transfer Learning using MobileNetV2
* Real-time image prediction
* Data augmentation for improved generalisation
* Performance evaluation using Accuracy, Precision, Recall, and F1-Score
* Streamlit web application for deployment

---

## Technologies Used

* Python
* TensorFlow / Keras
* MobileNetV2
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Streamlit

---

## Dataset

This project uses the PlantVillage Dataset containing images of healthy and diseased plant leaves.

Dataset Source:

https://www.kaggle.com/datasets/emmarex/plantdisease

---

## Model Architecture

* Input Image Size: 224 × 224
* Base Model: MobileNetV2 (Pre-trained on ImageNet)
* Global Average Pooling Layer
* Dropout Layer (0.3)
* Dense Output Layer with Softmax Activation

---

## Workflow

1. Data Collection
2. Data Preprocessing
3. Data Augmentation
4. Model Training
5. Model Evaluation
6. Disease Prediction
7. Streamlit Deployment

---

## Performance

### Test Results

* Test Accuracy: ~89%
* Low Test Loss
* Strong performance across multiple disease classes

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Sample Diseases Detected

* Bacterial Spot
* Early Blight
* Late Blight
* Leaf Mold
* Septoria Leaf Spot
* Target Spot
* Tomato Mosaic Virus
* Yellow Leaf Curl Virus
* Healthy Leaves

---

## Running the Project

### Clone Repository

```bash
git clone https://github.com/yourusername/plant-disease-detection-cnn.git
cd plant-disease-detection-cnn
```

### Install Requirements

```bash
pip install -r requirements.txt
```

### Run Streamlit Application

```bash
streamlit run app.py
```

---

## Future Improvements

* Support additional plant species
* Mobile application deployment
* Cloud deployment using Streamlit Cloud
* Multi-disease detection in a single image
* Explainable AI integration

---

## Author

**Gowry P P**

Data Science & AI Enthusiast
