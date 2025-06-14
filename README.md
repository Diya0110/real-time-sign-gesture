# real-time-sign-gesture
Bridging the communication gap with the speech and hearing impaired using real-time hand gesture recognition.

Real-Time Sign Language Detection Using Computer Vision-

A real-time hand gesture recognition system for translating sign language into readable text using computer vision and machine learning. This project leverages MediaPipe for hand landmark detection and a Random Forest Classifier for gesture classification.


Overview-<br>
Sign language is a vital communication method for individuals with hearing or speech impairments. Traditional systems rely on human interpreters or expensive hardware, which limits accessibility. This project presents a cost-effective, camera-based solution that enables real-time recognition of hand gestures representing alphabets and common words.


Problem Statement-<br>
1.Lack of real-time, scalable translation tools for sign language.<br>
2.High costs and complexity associated with sensor-based or hardware-heavy systems.<br>
3.Communication gaps between sign language users and the general public.


Objectives-<br>
1.Develop an AI-powered system capable of recognizing hand gestures using a standard webcam.<br>
2.Enable real-time gesture-to-text conversion using computer vision and machine learning techniques.<br>
3.Provide a foundation for future enhancements like speech synthesis and multilingual support.


Technologies Used-<br>
Python<br>
OpenCV – for image acquisition<br>
MediaPipe – for hand landmark detection<br>
Scikit-learn – for training the Random Forest Classifier<br>
Tkinter / OpenCV GUI – for real-time gesture display 


Workflow-<br>
Data Collection<br>
Captured 100–500 images per gesture using OpenCV.<br>
Dataset includes A–Z alphabets and basic words like "Hello" and "Thank You".<br>
Feature Extraction<br>
Detected 21 hand landmarks via MediaPipe.<br>
Extracted and normalized (x, y) coordinates for training.


Model Training-<br>
Used Random Forest Classifier.<br>
Achieved ~98% accuracy on validation data.<br>
Real-Time Prediction<br>
Real-time gesture recognition through webcam input.<br>
Display predicted gesture as text on screen.
