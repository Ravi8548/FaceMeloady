# 🎵 Music Generation Based on Facial Expression using YouTubeDL

An AI-driven project that detects facial expressions in real-time and generates or recommends music accordingly. By combining computer vision and deep learning for emotion detection with YouTubeDL for dynamic music retrieval, this system bridges the emotional state of the user with music that reflects or enhances their mood.

---

## 🚀 Features

- 🎯 Real-time **facial emotion detection** using OpenCV and CNN-based deep learning models.
- 🧠 Emotion-to-music **genre mapping** for mood-based personalization.
- 🎧 Automatically fetches and plays music from **YouTube** using the `youtube_dl` library.
- 💡 Lightweight and **interactive interface** for live testing and playback.

---

## 🧠 How It Works

1. Captures video frames from the webcam.
2. Detects facial landmarks and extracts emotion using a trained model.
3. Maps the detected emotion (e.g., Happy, Sad, Angry, Neutral) to a suitable music genre.
4. Uses `youtube_dl` to search and download a matching song from YouTube.
5. Plays the music using a system-level player or embedded audio module.

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**: OpenCV, TensorFlow/Keras, youtube_dl, NumPy, Pandas  
- **Model**: Pre-trained CNN for facial emotion recognition  
- **Other Tools**: VLC / playsound for audio playback (optional)

---

## 📁 Project Structure

