# 🖐️ Hand Gesture Game Controller

A real-time computer vision project that allows users to control PC games using hand movements detected through a webcam.

The project uses **OpenCV** for video processing, **MediaPipe** for hand landmark detection, and **PyDirectInput** to send keyboard inputs to the game.

---

## 🚀 Features

- 🎥 Real-time webcam input
- 🖐️ Real-time hand detection
- 📍 21-point hand landmark tracking using MediaPipe
- 👆 Index-finger position tracking
- ⬅️ Left-hand movement detection
- ➡️ Right-hand movement detection
- 🎮 Keyboard control using PyDirectInput
- ⚡ Real-time response
- 🖥️ Designed for PC games with keyboard controls

---

## 🧠 How It Works

The system follows this pipeline:

```text
Webcam
   ↓
OpenCV
   ↓
MediaPipe Hand Detection
   ↓
Hand Landmark Tracking
   ↓
Gesture / Position Detection
   ↓
PyDirectInput
   ↓
Keyboard Input
   ↓
PC Game
