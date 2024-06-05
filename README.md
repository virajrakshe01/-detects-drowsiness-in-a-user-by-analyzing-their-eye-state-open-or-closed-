# -detects-drowsiness-in-a-user-by-analyzing-their-eye-state-open-or-closed-
Design a system that detects drowsiness in a user by analyzing their eye state (open or closed) 

# Drowsiness Detection Project
This project aims to develop a real-time drowsiness detection system using machine learning algorithms. 
The system identifies whether a person's eyes are open or closed to detect drowsiness in real-time using a webcam.

## Overview
This project utilizes a pre-trained deep learning model to detect and classify the eye state (open or closed) in real-time. The model is trained to recognize drowsiness by analyzing the eye region in the webcam feed.

## Installation
To set up the project on your local machine, follow these steps:
1. Clone the repository or download and unzip it:
2. Create a virtual environment:
3. Activate the virtual environment:
4. Install the required packages:-  pip install tensorflow opencv-python

## Usage
To use the drowsiness detection model, follow these steps:

1. Ensure your webcam is connected and working.
2. Run the `untitled.ipynb` file:
3. The system will open a window displaying the webcam feed with detected faces and their corresponding eye states.
4. Press 'q' to quit the application.

 ## Model Description
The model used in this project is a Convolutional Neural Network (CNN) trained to detect whether eyes are open or closed. The key components are:

**Haar Cascade**: Used for face and eye detection.
- **Pre-trained CNN**: Used for classifying the eye state.

