🎵 FaceMelody – A Real-Time Facial Emotion-Based Music Recommender System 🎶
Built with Machine Learning | Computer Vision | YouTube-DL

🔍 Overview:
FaceMelody is an intelligent music recommendation system that uses real-time facial emotion recognition to suggest mood-based music. The system captures a person’s facial expressions using a webcam, processes the visual data using computer vision techniques, predicts the emotional state using a trained machine learning model, and automatically fetches and plays matching songs via YouTube using the youtube-dl module.

🧠 Core Technologies:

A) Machine Learning

* Custom-trained emotion detection model on real-time facial data
* Emotion classes include: Happy, Sad, Angry, Neutral, Surprised, etc.
* Model trained using OpenCV-captured datasets augmented with real-time facial features

B) Computer Vision

* Real-time facial feature detection using OpenCV
* Preprocessing includes grayscale conversion, histogram equalization, and face alignment
* Emotion classification using CNN-based architecture

C) youtube-dl Integration

* Dynamic retrieval of YouTube videos matching predicted emotion (e.g., "happy Bollywood songs")
* Automated playback using subprocess interface
* Minimal latency for real-time user response

🎯 Key Features:

* Personalized music experience based on current mood
* Lightweight desktop application interface
* Model trained on actual user’s facial data for high accuracy
* No pre-collected datasets — built entirely on real-time data acquisition

🚀 Outcome:
FaceMelody provides an emotionally adaptive entertainment experience. By combining real-time computer vision with machine learning and seamless integration with online media, this project showcases the intersection of emotion AI and multimedia personalization.

🛠️ Tools & Libraries Used:

* Python, OpenCV, TensorFlow/Keras, youtube-dl, NumPy, matplotlib
* Real-time webcam data capture and live model inference




