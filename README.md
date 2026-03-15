# 🤟 Sign Language Recognition & Voice-Based Mail System

> **Achieved 90% real-time gesture recognition accuracy** using CNN-based classification with OpenCV and TensorFlow/Keras — enabling hands-free email communication for users with hearing or speech impairments.

---

## 🎯 What It Does

A dual-mode accessibility system that lets users compose and send emails through either **hand sign gestures** (detected via webcam) or **voice commands** — no keyboard required.

- Real-time sign detection via webcam using OpenCV
- CNN model trained to classify hand gestures with **90% accuracy**
- Voice recognition pipeline for spoken email dictation
- Intuitive Tkinter GUI for compose, send, and navigation
- Designed for users with hearing or speech impairments

---

## 📸 Demo

**GUI Preview**

![GUI](https://user-images.githubusercontent.com/74150077/190896549-bbdc11d9-d953-4fb5-afbc-b31211b55f14.png)

**Live Demo Video**

https://private-user-images.githubusercontent.com/74150077/190897339-64115b4c-fc60-4391-9afa-fa72765cf149.mp4

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Language | Python 3.7.4 |
| ML Framework | TensorFlow 2.0, Keras 2.3.1 |
| Computer Vision | OpenCV 3.4.2 |
| GUI | Tkinter |
| Data Processing | NumPy 1.16.5 |
| IDE | Jupyter Notebook |

---

## 📁 Project Structure

```
sign-language-recognition/
│
├── imagecollection.ipynb     # Webcam-based image data collection
├── Label image.ipynb         # Dataset labeling and annotation
├── Tutorial.ipynb            # Model training and evaluation
├── tkinter.ipynb             # GUI application (compose & send email)
│
├── requirements.txt          # All dependencies
└── README.md
```

---

## ⚙️ Setup & Installation

### Prerequisites
- Python 3.7.4
- Webcam (for real-time gesture detection)

### 1. Clone the repository
```bash
git clone https://github.com/amisha2616/sign-language-recognition-And-voice-based-mail-system.git
cd sign-language-recognition-And-voice-based-mail-system
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Collect gesture data
Run `imagecollection.ipynb` to capture hand gesture images via webcam.

### 4. Label and train
Run `Label image.ipynb` to annotate images, then `Tutorial.ipynb` to train the CNN model.

### 5. Launch the application
Run `tkinter.ipynb` to start the GUI and begin composing emails via gestures or voice.

---

## 🧠 Model Performance

| Metric | Value |
|---|---|
| Accuracy | **90%** |
| Framework | TensorFlow / Keras CNN |
| Input | Real-time webcam frames |
| Preprocessing | OpenCV image normalization & resizing |

---

## ♿ Accessibility Impact

This project was built with accessibility at its core — providing an alternative communication channel for individuals who are deaf, hard of hearing, or speech-impaired. The dual-mode system (gesture + voice) ensures usability across a wider range of users and conditions.

---

## 👩‍💻 Author

**Amisha Sahu** — [LinkedIn](https://linkedin.com/in/amisha-sahu) · [GitHub](https://github.com/amisha2616)
