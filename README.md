# Hands-free-cursor-

# 🖱️ Cursor Movement by Hand Gesture

Control your mouse cursor using just your hand gestures! This project leverages **MediaPipe**, **OpenCV**, and **PyAutoGUI** to track your hand in real-time through a webcam and lets you move and click the mouse using gestures.

---

## 🧠 How It Works

- Tracks hand landmarks using **MediaPipe**.
- Uses the **index finger tip (ID 8)** to move the cursor.
- Detects a "pinch" gesture between the **index finger** and **thumb (ID 4)** to simulate a click.
- Uses `pyautogui` to control cursor and trigger click events.

---


### ✅ Prerequisites

Make sure Python 3.9 to 3.11 is installed and none are anacoda related otherwise DLL setup will fail. Then install the required libraries:

```bash
pip install mediapipe opencv-python pyautogui
