# driver-drowsiness-
# Emotion Analysis and Drowsiness Detection

This repository contains two Python scripts for emotion analysis and drowsiness detection using facial landmarks and CNN models. The scripts are implemented using OpenCV, Dlib, and TensorFlow/Keras libraries.

## Emotion Analysis

The `emotion_analysis.py` script captures video frames from the default camera (index 0) and performs emotion analysis on detected faces in real-time. It uses a pre-trained CNN model (`model.h5`) to predict the emotions of the detected faces. The emotions predicted are: angry, disgust, fear, happy, neutral, sad, and surprise. The predicted emotion labels are overlayed on the video frames.

### Prerequisites

- Python 3.x
- OpenCV
- Dlib
- Keras
- Numpy

### Usage

1. Install the required libraries using the following command:

2. Download the pre-trained CNN model (`model.h5`) and the face landmark predictor (`shape_predictor_68_face_landmarks.dat`) from the provided links in the code.

3. Run the `emotion_analysis.py` script using the following command:


4. The script will capture video frames from the default camera (index 0) and display the real-time emotion analysis results on the video frames. Press 'q' to stop the script.

## Drowsiness Detection

The `drowsiness_detection.py` script captures video frames from the default camera (index 0) and detects drowsiness in real-time based on facial landmarks. It uses a pre-trained CNN model (`CNNmodel.h5`) to predict whether the eyes are closed or open. If the predicted probability of closed eyes is above a threshold of 0.5, it indicates drowsiness. The drowsiness status is overlayed on the video frames.

### Prerequisites

- Python 3.x
- OpenCV
- Dlib
- TensorFlow/Keras

### Usage

1. Install the required libraries using the following command:


2. Download the pre-trained CNN model (`CNNmodel.h5`) and the face landmark predictor (`shape_predictor_68_face_landmarks.dat`) from the provided links in the code.

3. Run the `drowsiness_detection.py` script using the following command:


4. The script will capture video frames from the default camera (index 0) and display the real-time drowsiness detection results on the video frames. Press 'q' to stop the script.

Feel free to modify and experiment with the codes as per your requirements.

