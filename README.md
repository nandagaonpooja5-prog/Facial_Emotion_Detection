# Real-Time Multi-Face Emotion Detection System

## Project Overview

This project is a Real-Time Multi-Face Emotion Detection System developed using Computer Vision and Deep Learning. The system detects and tracks multiple faces through a live webcam feed and predicts facial emotions with confidence scores in real time.

The project uses:
- OpenCV for video processing and face detection
- DeepFace for emotion recognition
- Deep SORT for face tracking
- CNN-based deep learning for emotion analysis

Key capabilities:
- Multi-face detection and tracking
- Real-time emotion prediction
- Confidence score visualization
- Stable tracking IDs for each face

---

# Features

* Real-time webcam emotion detection
* Multi-face detection and tracking
* Emotion classification with confidence score
* Deep SORT based face tracking
* Bounding box visualization
* Live emotion labeling


---

# Technologies Used

## Programming Language

* Python

## Libraries and Frameworks

* OpenCV
* DeepFace
* NumPy
* Matplotlib
* Deep SORT Realtime
* Collections

---

# Project Workflow

## 1. Video Capture

The webcam captures live video frames continuously using OpenCV.

## 2. Face Detection

Faces are detected from each frame using Computer Vision techniques.

## 3. Face Tracking

Deep SORT tracker assigns unique IDs to detected faces and tracks them across multiple frames.

## 4. Emotion Analysis

Each detected face is analyzed using DeepFace to identify facial emotions.

## 5. Confidence Score Generation

The model predicts confidence scores for emotions such as:

* Happy
* Sad
* Angry
* Fear
* Surprise
* Neutral
* Disgust

## 6. Real-Time Visualization

Bounding boxes, emotion labels, tracking IDs, and confidence scores are displayed on the live webcam feed.

---

# Machine Learning and Deep Learning Concepts Used

* Convolutional Neural Networks (CNN)
* Facial Emotion Recognition
* Real-Time Object Tracking
* Computer Vision
* Feature Extraction
* Deep Learning Inference
* Confidence Score Prediction
* Multi-Object Tracking

---

# System Architecture

Input Webcam Feed
↓
OpenCV Frame Processing
↓
Face Detection
↓
Deep SORT Tracking
↓
DeepFace Emotion Analysis
↓
Emotion Prediction + Confidence Score
↓
Real-Time Visualization

---

# Installation

## Clone Repository

```bash
git clone <repository-link>
cd <repository-folder>
```

## Install Required Libraries

```bash
pip install opencv-python
pip install deepface
pip install numpy
pip install matplotlib
pip install deep-sort-realtime
```

---

# Run the Project

```bash
python app.py
```

The webcam will open and start detecting multiple faces with real-time emotion prediction.

---

# Output

The system displays:

* Face bounding boxes
* Tracking IDs
* Predicted emotions
* Emotion confidence scores
* Real-time tracking visualization

Example:

```text
ID 1 -> Happy (94%)
ID 2 -> Neutral (87%)
ID 3 -> Angry (79%)
```

---

# Applications

* Smart surveillance systems
* Human behavior analysis
* AI-based audience analytics
* Emotion-aware applications
* Mental health monitoring research
* Interactive AI systems
* Real-time engagement analysis

---

# Challenges Faced

* Real-time processing optimization
* Accurate emotion prediction under varying lighting conditions
* Multi-face tracking stability
* Reducing false detections
* Maintaining high FPS during live inference

---

# Future Improvements


* Integrate voice emotion recognition
* Deploy as a web application using Streamlit
* Add GPU acceleration
* Improve tracking accuracy
* Store emotion logs in database
* Add emotion trend visualization dashboard

---

# Results

The project successfully performs:

* Real-time multi-face detection
* Facial emotion classification
* Stable face tracking
* Confidence score prediction
* Live AI inference using Computer Vision and Deep Learning

---

# Skills Demonstrated

* Python Programming
* Computer Vision
* Deep Learning
* CNN Concepts
* Real-Time AI Systems
* OpenCV
* Emotion Recognition
* Multi-Object Tracking
* DeepFace Integration
* Model Inference
* AI Application Development

---

# Conclusion

This project demonstrates the implementation of a Real-Time Multi-Face Emotion Detection System using Deep Learning and Computer Vision techniques. By integrating OpenCV, DeepFace, and Deep SORT, the system achieves efficient emotion recognition, live face tracking, and confidence-based predictions in real time.

The project highlights practical AI application development and showcases skills in computer vision, deep learning inference, and real-time system design.
