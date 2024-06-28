# Facial-Emotion-Recognition-Using-Deep-Learning

## Overview
This project is a web application that performs real-time emotion recognition using a pre-trained deep learning model. The application consists of a Flask backend server and a JavaScript frontend, which together enable the detection and display of emotions from images captured via webcam.

## Features

- **Real-Time Emotion Recognition:** Detects emotions from live video feed or uploaded images.
- **Pre-Trained Model:** Utilizes a pre-trained TensorFlow/Keras model for emotion prediction.
- **Interactive Frontend:** User-friendly interface for capturing images and displaying predictions.
- **Secure and Accessible:** Uses Ngrok for secure tunneling and accessible testing from remote devices.

## Installation

### Prerequisites

- Python 3.x
- TensorFlow/Keras
- OpenCV
- Flask
- Ngrok

### Setup

1. **Clone the repository:**
   
   ```bash
   git clone https://github.com/your-username/emotion-recognition-app.git
   cd emotion-recognition-app

  pip install -r requirements.txt

Download the pre-trained model:

Ensure you have the pre-trained model (emotion_recognition_model.h5) in the models directory.

Running the Application

Start the Flask server:

python app.py

The application will be accessible at http://127.0.0.1:5000. If using Ngrok, use the public URL provided by Ngrok.

Usage

Open the web application in your browser.

Use the interface to capture an image using your webcam or upload an image file.

The application will display the detected emotion and confidence level.

Model and Preprocessing

The pre-trained model is a TensorFlow/Keras model trained for emotion recognition.

Image preprocessing includes converting to grayscale, resizing to 48x48 pixels, normalizing pixel values, and converting to an array for model input.
