# GestuTalk: Sign Language to Text and Speech Converter

*GestuTalk* is a real-time sign language interpretation system that translates hand gestures into text and speech using computer vision and deep learning. It aims to bridge the communication gap for the hearing and speech impaired by enabling seamless interactions through an intuitive interface.

---

## 🧠 Tech Stack

| Component        | Technology Used                         |
|------------------|------------------------------------------|
| Hand Tracking     | MediaPipe                                |
| Video Processing  | OpenCV                                   |
| Gesture Classification | TensorFlow (Trained ML Model)        |
| GUI               | Kivy                                     |
| Text-to-Speech    | pyttsx3                                  |

---

## ✨ Key Features

- 🖐 Supports both *one-hand* and *two-hand* gestures
- 📷 *Real-time* gesture detection and text conversion
- 🔊 *Voice narration* of detected signs using pyttsx3
- 💡 Lightweight, modular, and easily extensible
- 🧩 Simple, clean, and *user-friendly interface*

---

## 📸 How It Works

1. *Image Capture*: Captures real-time images feed from webcam using OpenCV.
2. *Hand Detection*: Uses MediaPipe to detect hand landmarks.
3. *Gesture Classification*: A TensorFlow model classifies gestures based on hand position and shape.
4. *Text & Speech Output*: The gesture is converted into text and spoken aloud using pyttsx3.
5. *GUI Display*: Outputs and controls are managed through a Kivy-based interface.

---

## 🛠 How to Use

1. *Collect Gesture Data*  
   Run the data collection module to capture gesture images using your webcam. Each gesture is saved under its label.

2. *Structure the Dataset*  
   Process the collected images to extract hand landmarks and generate a structured CSV file for training.

3. *Train the Model*  
   Use the structured data to train the gesture recognition model. This will create the trained model and label encoder.

4. *Run the Application*  
   Launch the main application with GUI. Perform gestures in front of the camera to see real-time text and hear voice output.

---

That's it! GestuTalk is now ready for real-time sign-to-speech conversion.
