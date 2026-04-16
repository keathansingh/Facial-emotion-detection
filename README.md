
# Facial Emotion Recognition using VGG Model

![Python](https://img.shields.io/badge/Python-3.9-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![CNN](https://img.shields.io/badge/Model-CNN-green)
![Dataset](https://img.shields.io/badge/Dataset-FER2013-yellow)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-lightgrey)

## Project Overview

Facial Emotion Recognition (FER) is an **Artificial Intelligence application that detects human emotions from facial expressions** using computer vision and deep learning.

This project builds a **CNN-based deep learning model** trained on the **FER2013 dataset** to classify facial expressions into emotional categories.

The model analyzes grayscale facial images and predicts emotions such as **happy, sad, angry, surprised, fear, disgust, and neutral**.

---

## Key Features

* Deep learning-based facial emotion detection
* CNN / VGG-like architecture
* FER2013 dataset implementation
* Data preprocessing and augmentation
* Visualization of emotion distributions
* Model evaluation and prediction

---

## Dataset

This project uses the **FER2013 dataset**, widely used for emotion recognition research.

Dataset characteristics:

| Feature      | Value     |
| ------------ | --------- |
| Total Images | ~35,000   |
| Image Size   | 48 × 48   |
| Image Type   | Grayscale |
| Format       | CSV       |

### Emotion Classes

The model predicts **7 emotions**:

1. Angry
2. Disgust
3. Fear
4. Happy
5. Sad
6. Surprise
7. Neutral

---

## Technologies Used

### Programming Language

* Python

### Development Platform

* Google Colab

### Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* TensorFlow
* Keras

---

## Project Workflow

### 1 Data Loading

The FER2013 dataset is loaded from a CSV file containing pixel values and emotion labels.

### 2 Data Preprocessing

* Convert pixel strings into arrays
* Reshape images into **48×48 grayscale format**
* Normalize pixel values
* Split dataset into training and validation sets

### 3 Data Visualization

* Visualize emotion distribution
* Display sample facial images

### 4 Model Architecture

A **CNN / VGG-like architecture** is used consisting of:

* Convolution layers
* MaxPooling layers
* Dropout layers
* Fully connected dense layers
* Softmax output layer

### 5 Data Augmentation

To improve model generalization:

* Horizontal flip
* Rotation
* Zoom
* Shift transformations

### 6 Model Training

| Parameter     | Value                    |
| ------------- | ------------------------ |
| Optimizer     | Adam                     |
| Loss Function | Categorical Crossentropy |
| Metric        | Accuracy                 |

### 7 Model Evaluation

Model performance is evaluated using:

* Training accuracy
* Validation accuracy
* Loss curves
* Emotion prediction visualization

---

## Input Features

The model takes the following input:

* Grayscale facial images
* Image size: **48 × 48 pixels**
* Pixel intensity values

---

## Output

The model outputs a predicted emotion label from the following classes:

* Angry
* Disgust
* Fear
* Happy
* Sad
* Surprise
* Neutral

---

## Applications

Facial emotion recognition can be applied in many domains:

* Mental health monitoring
* Smart classroom engagement systems
* Customer sentiment analysis
* Human-computer interaction
* Driver fatigue detection
* Security and surveillance systems

---

## Limitations

Some challenges of facial emotion recognition include:

* Sensitivity to lighting conditions
* Cultural variations in emotional expressions
* Occlusion issues (masks, glasses)
* Dataset bias

---

## Future Improvements

Potential improvements for this project include:

* Real-time emotion detection using webcam
* Integration with OpenCV
* Transfer learning with pretrained models
* Multimodal emotion detection (voice + facial expressions)
* Explainable AI techniques such as Grad-CAM or SHAP

---

## Project Structure

```
Facial-Emotion-Recognition
│
├── dataset
│   └── fer2013.csv
│
├── notebooks
│   └── FacialEmotionVGG.ipynb
│
├── images
│   └── sample_output.png
│
├── requirements.txt
│
└── README.md
```

---

## Installation

Clone the repository

```
git clone https://github.com/your-username/facial-emotion-recognition.git
```

Navigate to the project directory

```
cd facial-emotion-recognition
```

Install dependencies

```
pip install -r requirements.txt
```

Run the notebook in **Google Colab or Jupyter Notebook**.

---

## Results

The CNN model successfully learns facial features and predicts emotional expressions with reasonable accuracy on the FER2013 dataset.

The project demonstrates how deep learning can be applied to **emotion-aware AI systems**.

---

## Author

**Hemasri Sanchula**

---
