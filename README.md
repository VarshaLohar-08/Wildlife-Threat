# 🌲 ForestGuard – AI-Based Environmental Sound Classification

##  Overview

ForestGuard is a Deep Learning-based environmental sound classification system designed to identify and classify various forest and environmental sounds from audio recordings. The project converts raw audio signals into Mel-Spectrogram images and uses a Convolutional Neural Network (CNN) built with PyTorch to recognize different sound categories.

The system can be used for intelligent forest monitoring, wildlife conservation, biodiversity assessment, and early detection of abnormal events such as illegal logging, chainsaw activity, gunshots, or fire-related sounds.

---

##  Objectives

* Develop an automated environmental sound classification system.
* Convert raw audio recordings into meaningful features using Mel-Spectrograms.
* Train a CNN model to accurately classify environmental sounds.
* Reduce manual monitoring efforts using AI-powered sound recognition.
* Demonstrate the application of Deep Learning in environmental conservation.

---

##  Features

* Audio preprocessing and cleaning
* Mel-Spectrogram feature extraction
* CNN-based Deep Learning model
* Model training and validation
* Performance evaluation using accuracy and loss metrics
* Visualization of audio signals and spectrograms
* Model saving and loading for inference

---

##  Technologies Used

### Programming Language

* Python

### Deep Learning

* PyTorch

### Machine Learning

* Scikit-learn

### Audio Processing

* Librosa

### Data Processing

* NumPy
* Pandas

### Visualization

* Matplotlib

### Development Environment

* Jupyter Notebook

### Version Control

* Git
* GitHub

---

##  Dataset

The project uses the **ESC-50 (Environmental Sound Classification)** dataset.

The dataset contains 2,000 labeled environmental audio recordings across 50 sound categories, including:

* Rain
* Dog Bark
* Bird Chirping
* Fire Crackling
* Chainsaw
* Helicopter
* Wind
* Clock Tick
* Water Drops
* Engine Sounds
* Thunderstorm
* And many more.

---

##  Project Workflow

```text
Audio Dataset
       │
       ▼
Audio Loading (Librosa)
       │
       ▼
Audio Preprocessing
       │
       ▼
Mel-Spectrogram Generation
       │
       ▼
Feature Normalization
       │
       ▼
CNN Model (PyTorch)
       │
       ▼
Training
       │
       ▼
Validation
       │
       ▼
Prediction
       │
       ▼
Performance Evaluation
```

---

##  Model Architecture

The project uses a **Convolutional Neural Network (CNN)** consisting of:

* Convolution Layers
* ReLU Activation
* Max Pooling
* Dropout Layer
* Fully Connected Layers
* Softmax Output Layer

The CNN automatically learns important spatial features from Mel-Spectrograms for accurate environmental sound classification.

---

##  Evaluation Metrics

The model performance is evaluated using:

* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss

These metrics help monitor model learning and detect overfitting.

---

##  Project Structure

```
ForestGuard/
│
├── Dataset/
├── Audio Files/
├── CNN Training Notebook
├── Model Checkpoints
├── README.md
├── requirements.txt
└── Saved Model
```

---

## 💡 Applications

* Smart Forest Monitoring
* Wildlife Conservation
* Biodiversity Assessment
* Environmental Sound Recognition
* Illegal Logging Detection
* Forest Fire Early Warning
* Smart IoT Environmental Monitoring

---

##  Future Enhancements

* Real-time audio classification
* IoT-based forest monitoring devices
* Mobile application support
* Cloud deployment
* Edge AI implementation
* Transformer-based audio classification models
* Live alert system for abnormal sounds

---

##  Skills Demonstrated

* Python Programming
* Deep Learning
* Convolutional Neural Networks (CNN)
* Audio Signal Processing
* Environmental Sound Classification
* Feature Engineering
* Data Preprocessing
* Model Training & Validation
* Performance Evaluation
* PyTorch
* Librosa
* Machine Learning

---

##  Author

**Varsha Lohar**

AI & Machine Learning Enthusiast | Deep Learning | Python | Environmental Sound Classification

---

## 📄 License

This project is developed for educational and research purposes.
