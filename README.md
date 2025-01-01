# Drowsy Driver Detection System  

Real-time detection and mitigation of driver fatigue are critical to ensuring road safety. This project implements a **Drowsy Driver Detection and Alarm System** that uses **computer vision** and **machine learning techniques** to monitor driver wakefulness and prevent accidents caused by drowsiness.  

## Features  
- **Facial and Ocular Feature Detection**: Utilizes Haar cascade classifiers from the OpenCV library to accurately track a driver's face and eyes.  
- **Deep Learning Model**: Employs a Convolutional Neural Network (CNN) trained on fatigue-related facial and eye datasets to classify driver states as awake or asleep.  
- **Real-Time Alerts**: Triggers audible or visual alarms to warn drivers when signs of fatigue are detected, reducing the risk of accidents.  
- **Versatile Integration**: Designed for easy embedding in automotive platforms or existing driver assistance systems.  

## Technologies Used  
- **OpenCV**: For real-time facial and ocular feature tracking.  
- **Haar Cascade Classifier**: For detecting faces and eyes.  
- **Convolutional Neural Network (CNN)**: For analyzing facial features and predicting driver drowsiness.  
- **Python**: Primary programming language for implementation.  

## How It Works  
1. **Feature Detection**: The Haar cascade classifier tracks the driver's face and eyes in real-time.  
2. **Deep Learning Classification**: The CNN model predicts driver drowsiness based on identified features.  
3. **Alert System**: Audible or visible alerts are raised when the driver shows signs of fatigue.  

## Use Cases  
- **Road Safety**: Prevent accidents by monitoring and alerting drivers in real-time.  
- **Automotive Integration**: Embed the system into vehicles for enhanced driver assistance.  
- **Custom Applications**: Install in various platforms requiring driver monitoring and safety features.  

## Installation and Usage  
1. Clone the repository:
   ```git clone https://github.com/Mathesh-V/Drowsy-Driver-Detection-System.git  
