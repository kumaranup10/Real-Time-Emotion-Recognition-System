# Real-Time Emotion Recognition System

## 📌 Project Overview

The Real-Time Emotion Recognition System is a computer vision and deep learning-based application that detects human emotions from facial expressions in real time. The system captures video through a webcam, detects faces, and classifies emotions such as Happy, Sad, Angry, Fear, Surprise, Disgust, and Neutral using a Convolutional Neural Network (CNN).

This project demonstrates the integration of Computer Vision, Deep Learning, and Real-Time Analytics to create an intelligent emotion detection system.

---

## 🚀 Features

- Real-time face detection using webcam
- Emotion classification using CNN
- Supports 7 emotion categories:
  - Happy 😊
  - Sad 😔
  - Angry 😠
  - Fear 😨
  - Surprise 😲
  - Disgust 🤢
  - Neutral 😐
- Live emotion display on video feed
- High accuracy emotion prediction
- Lightweight and easy to deploy

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries & Frameworks
- OpenCV
- TensorFlow
- Keras
- NumPy
- Matplotlib

### Deep Learning
- Convolutional Neural Network (CNN)

### Development Tools
- Jupyter Notebook
- VS Code

---

## 📂 Dataset

This project uses the **FER-2013 (Facial Expression Recognition 2013)** dataset.

### Dataset Details
- Total Images: 35,887
- Image Size: 48 × 48 pixels
- Type: Grayscale Images
- Emotion Classes:
  - Angry
  - Disgust
  - Fear
  - Happy
  - Sad
  - Surprise
  - Neutral

Dataset Link:
https://www.kaggle.com/datasets/msambare/fer2013

---

## ⚙️ System Architecture

```text
Webcam Input
      │
      ▼
Face Detection (OpenCV)
      │
      ▼
Image Preprocessing
      │
      ▼
CNN Model
      │
      ▼
Emotion Prediction
      │
      ▼
Display Result
```

---

## 🔄 Working Procedure

1. Capture video from webcam.
2. Detect face using OpenCV Haar Cascade.
3. Convert image into grayscale format.
4. Resize image according to model requirements.
5. Feed image into trained CNN model.
6. Predict emotion.
7. Display detected emotion on screen in real time.

---

## 📊 Model Performance

### Key Metrics
- Accuracy: ~90%
- Real-Time Emotion Detection
- Low Latency Prediction

---

## 📁 Project Structure

```text
Real-Time-Emotion-Recognition/
│
├── dataset/
├── model/
│   ├── emotion_model.h5
│
├── haarcascade/
│   ├── haarcascade_frontalface_default.xml
│
├── notebooks/
│   ├── training.ipynb
│
├── src/
│   ├── emotion_detection.py
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ▶️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/Real-Time-Emotion-Recognition.git
```

### Navigate to Project Folder

```bash
cd Real-Time-Emotion-Recognition
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python emotion_detection.py
```

The webcam will start automatically and display the detected emotion in real time.

---

## 📈 Applications

- Mental Health Monitoring
- Smart Classrooms
- Human Computer Interaction
- Customer Feedback Analysis
- Healthcare Systems
- Emotion-Aware Virtual Assistants
- Smart Surveillance Systems

---

## 🔮 Future Enhancements

- Multi-face emotion detection
- Voice and emotion analysis integration
- Mobile application deployment
- Emotion trend analytics dashboard
- Improved accuracy using advanced deep learning models

---

## 👥 Team Members

- Kumar Anup
- Lakshya Garg
- Abhishek Gond
- Kratika Nigam
- Ayush Yadav

---

## 📜 License

This project is developed for educational and research purposes.

---

## ⭐ Acknowledgements

- FER-2013 Dataset
- OpenCV Community
- TensorFlow & Keras
- Kaggle
