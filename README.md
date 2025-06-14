# real-time-sign-gesture
Bridging the communication gap with the speech and hearing impaired using real-time hand gesture recognition.

Real-Time Sign Language Detection Using Computer Vision-

A real-time hand gesture recognition system for translating sign language into readable text using computer vision and machine learning. This project leverages MediaPipe for hand landmark detection and a Random Forest Classifier for gesture classification.


Overview-
Sign language is a vital communication method for individuals with hearing or speech impairments. Traditional systems rely on human interpreters or expensive hardware, which limits accessibility. This project presents a cost-effective, camera-based solution that enables real-time recognition of hand gestures representing alphabets and common words.


Problem Statement-
1.Lack of real-time, scalable translation tools for sign language.
2.High costs and complexity associated with sensor-based or hardware-heavy systems.
3.Communication gaps between sign language users and the general public.


Objectives-
1.Develop an AI-powered system capable of recognizing hand gestures using a standard webcam.
2.Enable real-time gesture-to-text conversion using computer vision and machine learning techniques.
3.Provide a foundation for future enhancements like speech synthesis and multilingual support.


Technologies Used-
Python
OpenCV – for image acquisition
MediaPipe – for hand landmark detection
Scikit-learn – for training the Random Forest Classifier
Tkinter / OpenCV GUI – for real-time gesture display (optional)


Workflow-
Data Collection
Captured 100–500 images per gesture using OpenCV.
Dataset includes A–Z alphabets and basic words like "Hello" and "Thank You".
Feature Extraction
Detected 21 hand landmarks via MediaPipe.
Extracted and normalized (x, y) coordinates for training.


Model Training-
Used Random Forest Classifier.
Achieved ~98% accuracy on validation data.
Real-Time Prediction
Real-time gesture recognition through webcam input.
Display predicted gesture as text on screen.
