Emotion Recognition with Real-Time Detection

This project focuses on real-time emotion recognition using computer vision techniques and a trained deep learning model. The system can detect emotions such as Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral from facial expressions captured through a webcam feed. The project also includes a graphical user interface (GUI) that allows users to analyze images from their local storage.

Table of Contents

Introduction
Features
Dataset
Real-Time Detection
Graphical User Interface (GUI)
Getting Started
Dependencies
Usage
Contributions
License
Introduction

Emotion recognition is an essential part of human-computer interaction and has numerous applications, including personalized user experiences, content recommendation, and mental health analysis. This project leverages a pre-trained deep learning model to accurately identify emotions from facial expressions in real-time.

Features

Real-time emotion detection using a webcam feed.
GUI for loading and analyzing images from local storage.
Emotion classification into categories: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.
Display of predicted emotions on images.
Utilization of OpenCV for face detection and image processing.
Integration with a trained deep learning model for accurate emotion classification.
Dataset

The project employs a dataset consisting of labeled facial expressions corresponding to different emotions. This dataset plays a crucial role in training the deep learning model. The model learns to identify patterns in facial features associated with each emotion category.

Real-Time Detection

The real-time emotion detection feature captures video frames from a webcam feed, detects faces using OpenCV's Haarcascade classifier, and applies the trained deep learning model to predict emotions for each detected face. The predicted emotion is then displayed in real-time, enabling instant analysis of the person's emotional state.

Graphical User Interface (GUI)

The GUI provides an interactive way to load and process images for emotion recognition. Users can choose an image from their local storage, and the system will display the loaded image along with the predicted emotion. The GUI simplifies the process of analyzing images and understanding the model's performance.

Getting Started

To use this project locally, follow these steps:

Clone this repository: git clone https://github.com/Chaitanyakota9/Real-time-Emotion-detection-GUI-.git
Install the required dependencies (see Dependencies).
Download the pre-trained model weights and place them in the project directory.
Run the project by executing the main script.
Dependencies

Python (>=3.6)
OpenCV (cv2)
NumPy
TensorFlow (or other backend for Keras)
PIL (Pillow)

You can install the required dependencies using pip:

pip install opencv-python numpy tensorflow pillow


Run the main script to start the real-time emotion detection or open the GUI for image analysis.
Real-Time Detection: The webcam feed will display frames with predicted emotions overlaid on detected faces.
GUI: Click on the "Open Image" button to choose an image for analysis. The GUI will display the loaded image along with the predicted emotion.
