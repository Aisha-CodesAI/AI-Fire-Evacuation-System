# AI-Fire-Evacuation-System
AI-powered fire detection and smart evacuation system using computer vision and AI
# 🔥 AI Fire Evacuation System (AION Evacuate)

## 🚀 Overview
AION Evacuate is an AI-powered emergency system that detects fire in real-time using computer vision and generates the safest evacuation path using a building blueprint.

The system works with multiple input sources like webcam, images, videos, and screen capture, making it suitable for real-world environments such as colleges, hospitals, and public spaces.

---

## 🎯 Problem Statement
In fire emergencies, people panic and do not know the safest exit route. Traditional alarms only alert but do not guide.

---

## 💡 Solution
This system:
- Detects fire using AI
- Maps fire location on a real blueprint
- Generates a safe evacuation path
- Gives voice alerts
- Provides AI-based guidance

---

## ✨ Features

### 🔥 Fire Detection
- Webcam (live)
- Uploaded images
- Uploaded videos
- YouTube videos
- Screen capture (detect from screen)

---

### 🗺️ Evacuation Map
- Uses real blueprint (floor plan)
- Shows:
  - 🔴 Fire location
  - 🔵 User location
  - 🟢 Safe path
  - 🟡 Exit points

---

### 🎥 Camera System
- Real webcam
- Uploaded images (simulate CCTV)
- Video input
- Detection shown directly on camera feed

---

### 🔊 Voice Alerts
- Real-time alerts using text-to-speech
- Example:
  Fire detected. Please follow the evacuation route.

---

### 🤖 AI Assistant
- Voice + text interaction
- Answers safety questions
- Guides user to exits

---

## 🧠 Tech Stack
- Python
- Streamlit
- OpenCV
- NumPy
- Gemini API
- gTTS (voice)

---

## 📂 Project Structure
project/ ├── app.py ├── fire_ai.py ├── evacuation_ai.py ├── chatbot.py ├── utils.py ├── video_source.py ├── requirements.txt ├── README.md

---

## ⚙️ Setup Instructions

### 1. Clone Repository
git clone https://github.com/Aisha-CodesAI/AI-Fire-Evacuation-System.git⁠� cd AI-Fire-Evacuation-System

### 2. Install Requirements
pip install -r requirements.txt

### 3. Add API Key
Create `.env` file:
GEMINI_API_KEY=your_api_key_here

### 4. Run App
streamlit run app.py

---

## 🎥 Demo Video
(Add your 3-minute demo link here)

---

## 🌐 Live MVP
(Add your deployed app link here)

---

## 👥 Team Members
- Aisha Erum – AI & Backend
- [Mahira Firdous] – Frontend/UI
- [Zoya Akbar] – Integration

---

## 🚀 Future Scope
- Better AI model (YOLO)
- Mobile app
- Crowd detection
- IoT integration

---

## 🏆 Impact
Can be used in:
- Colleges
- Hospitals
- Hotels
- Offices

Helps people evacuate safely during emergencies.

---

## 📌 Conclusion
This is not just a fire detection system, but an intelligent evacuation system that guides users in real-time.

---
