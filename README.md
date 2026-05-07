````markdown
# ASL Detection - Real-Time Sign Language Recognition

A real-time American Sign Language (ASL) detection system built using Convolutional Neural Networks (CNNs), OpenCV, and Python.

The project recognizes all 26 ASL alphabet gestures directly from webcam input and performs live inference with optimized prediction speed and accuracy.

---

# Features

- Real-time ASL alphabet recognition
- Detects all 26 ASL gestures
- Live webcam-based prediction
- CNN model built and trained from scratch
- Image preprocessing using OpenCV
- Dataset augmentation and normalization
- Real-time inference pipeline
- Performance evaluation and hyperparameter tuning

---

# Tech Stack

## Languages
- Python

## Libraries & Frameworks
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib

---

# Model Overview

The project uses a Convolutional Neural Network (CNN) trained on grayscale ASL gesture images.

### Pipeline

```text
Webcam Feed
      ↓
Frame Capture
      ↓
Image Preprocessing
      ↓
Grayscale Conversion
      ↓
Resizing & Normalization
      ↓
CNN Prediction
      ↓
Real-Time Gesture Classification
````

---

# Dataset

* ASL Alphabet Dataset
* 78,000+ grayscale training images
* 26 gesture classes (A-Z)

---

# Key Features Implemented

* Real-time webcam integration using OpenCV
* CNN-based image classification
* Data preprocessing and augmentation
* Hyperparameter tuning experiments
* Live prediction visualization
* Performance tracking and evaluation

---

# Model Performance

| Metric        | Value            |
| ------------- | ---------------- |
| Test Accuracy | 94.2%            |
| Classes       | 26               |
| Dataset Size  | 78,000+ Images   |
| Input Type    | Grayscale Images |

---

# Installation

## Clone Repository

```bash
git clone https://github.com/harshiit-rana/ASL_Detection.git
cd ASL_Detection
```

---

# Create Virtual Environment

## Windows

```bash
python -m venv venv
venv\Scripts\activate
```

## Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

# Install Dependencies

```bash
pip install -r requirements.txt
```

or manually:

```bash
pip install tensorflow
pip install opencv-python
pip install numpy
pip install pandas
pip install matplotlib
```

---

# Run the Project

```bash
python main.py
```

or run the notebook if included:

```bash
jupyter notebook
```

---

# Project Structure

```text
ASL_Detection/
│
├── dataset/
├── models/
├── outputs/
├── main.py
├── train.py
├── requirements.txt
└── README.md
```

---

# Challenges Faced

* Real-time prediction latency optimization
* Webcam frame preprocessing consistency
* Overfitting reduction during CNN training
* Gesture similarity between multiple ASL classes

---

# Future Improvements

* Word-level ASL recognition
* Sentence formation support
* Transformer-based gesture recognition
* Mobile deployment
* MediaPipe hand tracking integration
* Speech output for detected gestures

---

# Resume Highlights

* Built a CNN-based ASL recognition system capable of real-time gesture detection
* Trained on 78,000+ images with optimized preprocessing and augmentation pipelines
* Achieved 94.2% test accuracy after iterative hyperparameter tuning
* Integrated OpenCV webcam pipelines for live inference

---

# Author

Harshit Rana

