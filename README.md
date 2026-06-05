# Facial Expression Recognition Using Convolutional Neural Networks (CNN)

## Overview

This project uses Deep Learning and Computer Vision techniques to classify human facial expressions into seven emotion categories. A Convolutional Neural Network (CNN) was trained on the FER-2013 dataset to recognize emotions from grayscale facial images.

The project demonstrates image preprocessing, data augmentation, model training, performance evaluation, and emotion prediction using TensorFlow and Keras.

---

## Features

- Facial emotion classification using CNNs
- Data augmentation to improve model generalization
- Training and validation performance visualization
- Confusion matrix and classification report evaluation
- Emotion prediction on new facial images
- FER-2013 dataset implementation

---

## Emotions Classified

The model predicts the following seven emotions:

- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

---

## Dataset

**FER-2013 (Facial Expression Recognition 2013)**

Dataset Characteristics:

- 28,709 training images
- 7,178 testing images
- 48 × 48 grayscale facial images
- 7 emotion classes

Dataset Source:
https://www.kaggle.com/datasets/msambare/fer2013

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Model Architecture

The Convolutional Neural Network consists of:

- Convolutional Layers
- Max Pooling Layers
- Dropout Layers
- Fully Connected Dense Layers
- Softmax Output Layer

The model was trained using categorical cross-entropy loss and the Adam optimizer.

---

## Results

### Performance Metrics

- Test Accuracy: **59%**
- 7 Emotion Categories
- Classification Report Included
- Confusion Matrix Included

### Evaluation

The model performed best on emotions such as:

- Happy
- Surprise
- Neutral

More challenging classes included:

- Disgust
- Fear

This reflects common challenges found in facial expression recognition datasets due to class imbalance and visual similarity between emotions.

---

## Project Workflow

1. Load and preprocess FER-2013 dataset
2. Apply image augmentation techniques
3. Build CNN architecture
4. Train model using TensorFlow/Keras
5. Evaluate model performance
6. Generate confusion matrix and classification report
7. Predict emotions from new images

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/facial-expression-recognition.git
```

2. Install required libraries

```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn
```

3. Open and run:

```bash
facial_expression_recognition.ipynb
```

---

## Skills Demonstrated

- Deep Learning
- Computer Vision
- Convolutional Neural Networks (CNNs)
- Data Preprocessing
- Model Evaluation
- TensorFlow/Keras Development
- Machine Learning Experimentation

---

## Future Improvements

- Transfer Learning with ResNet or EfficientNet
- Hyperparameter Optimization
- Real-Time Webcam Emotion Detection
- Improved Class Balancing Techniques
- Deployment as a Web Application

---

## Author

**Amanuel Gedeb**

Computer Science Graduate | Early Entry Master's Student in Artificial Intelligence

GitHub: https://github.com/AmanuelTenaw
