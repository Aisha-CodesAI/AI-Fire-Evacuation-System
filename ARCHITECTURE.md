# Architecture

# 🧠 System Architecture

## Overview
This project follows a layered architecture for real-time fire detection and evacuation guidance.

---

## 📊 Architecture Diagram

![Architecture](architecture diagram.jpeg)

---

## 🔹 1. Input Layer
- Webcam (live feed)
- Image upload
- Video / YouTube input
- Screen capture

---

## 🔹 2. Processing Layer
- Frame capture
- Fire detection using OpenCV
- Color filtering (HSV)
- Contour detection
- Bounding box detection

---

## 🔹 3. Decision Layer
- Check if fire is detected
- Trigger alert system
- Send fire location to map module

---

## 🔹 4. Evacuation Engine
- Uses blueprint (floor plan)
- Identifies:
  - User location
  - Fire location
  - Safe exit routes
- Generates safest path

---

## 🔹 5. Output Layer
- Camera feed with detection overlay
- Evacuation map
- Voice alert (gTTS)
- AI Assistant (Gemini)

---

## 🔹 6. Platform Layer
- Built using Base44
- Handles UI, integration, and logic

---

## 🔄 System Flow
Input → Detection → Decision → Path Generation → Output

---

## 🎯 Goal
To detect fire in real-time and guide users safely using intelligent evacuation paths.
