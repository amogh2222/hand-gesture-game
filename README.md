# 🖐️ Index Finger Swipe Controller

A real-time gesture recognition system using your **index finger swipes** to simulate arrow key presses (`up`, `down`, `left`, `right`) with a webcam. Built using OpenCV, MediaPipe, and PyAutoGUI.

## 📹 Demo

<img src="https://img.shields.io/badge/Demo-coming%20soon-blue" alt="Demo coming soon">

## ✨ Features

- Track **index finger tip** in real time using MediaPipe
- Detect **directional swipe gestures** (up, down, left, right)
- Trigger arrow key events based on gestures
- Visual feedback on detected gestures and hand landmarks

## 🚀 How It Works

- The webcam captures your hand movements.
- MediaPipe detects hand landmarks.
- The program monitors the index fingertip’s position.
- On a significant swipe, it simulates an arrow key press via PyAutoGUI.
- A cooldown mechanism prevents accidental multiple triggers.

## 🛠️ Requirements

Install dependencies via pip:

```bash
pip install -r requirements.txt
