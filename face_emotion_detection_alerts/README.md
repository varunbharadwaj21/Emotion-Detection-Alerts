
# Face Emotion Detection with Attention Alerts

An AI-powered real-time system that detects facial emotions, drowsiness, gaze direction, and yawning through webcam input using MediaPipe, TensorFlow, and OpenCV. Alerts are triggered via sound and visual warnings for fatigue, attention loss, or distraction.

---

## 🚀 Features

- 🎭 **Facial Emotion Detection** (7 emotions)
- 💤 **Drowsiness Detection** using Eye Aspect Ratio (EAR)
- 😮 **Yawn Detection** via mouth opening distance
- 👁️ **Gaze Detection** to detect if user is looking away
- 🔊 **Sound Alerts** for drowsiness and attention loss
- 🧩 **Facial Landmark Visualization**

---

## 📦 Folder Structure

```
face-emotion-detection-alerts/
│
├── Face_Emotion_Detection_with_Alerts.py   # Main Python script
├── alert.mp3                               # Audio alert file
├── emotion_model.h5                        # Pre-trained emotion model (FER-2013 based)
├── requirements.txt                        # Dependencies
└── README.md                               # Project documentation
```

---

## 🖥️ Setup Instructions

### ✅ 1. Clone the Repository
```bash
git clone https://github.com/yourusername/face-emotion-detection-alerts.git
cd face-emotion-detection-alerts
```

### ✅ 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### ✅ 3. Run the Script
```bash
python Face_Emotion_Detection_with_Alerts.py
```

Make sure to place `emotion_model.h5` and `alert.mp3` in the same directory.

---

## 🔍 Use Cases

- **🚗 Driver Monitoring Systems:** Alerts drowsy or inattentive drivers.
- **🎓 E-Learning Platforms:** Monitor student attention and engagement.
- **🏢 Corporate Productivity:** Ensure employee alertness in critical tasks.
- **🎮 Gaming / VR Systems:** Adapt gameplay based on user emotions.
- **🎥 User Feedback Systems:** Collect emotional responses during product demos or media consumption.

---

## 🎯 Requirements
- Python 3.8+
- TensorFlow
- MediaPipe
- OpenCV
- Numpy
- playsound

---

## 🤝 Contributing
Feel free to fork the project, create issues, and submit pull requests. Contributions for:
- Improved gaze detection
- Support for more emotions
- Multilingual sound alerts
are welcome!

---

## 📜 License
[MIT License](LICENSE)

---

## 🙌 Credits
- [MediaPipe](https://mediapipe.dev/)
- [TensorFlow](https://www.tensorflow.org/)
- [FER-2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013)

---

For queries or collaborations, feel free to reach out!

---
