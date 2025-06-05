# Hand-Controlled-Driving-Simulator

# 🖐️ Hand Gesture Car Control 🚗💨  

Control your car using hand gestures detected by your webcam!  
This project uses **MediaPipe** for hand tracking, **OpenCV** for video processing, and **pynput** to simulate keyboard inputs for controlling a car in any compatible game or simulation.
  

##  📸 Features
- ✋ Detects one hand using your webcam
- 🟢 All fingers open = **Accelerate** (presses ➡️ Right Arrow)
- 🔴 All fingers closed = **Brake** (presses ⬅️ Left Arrow)
- 🧠 Real-time hand tracking using MediaPipe
- 🎮 Can be used with driving games or simulations 


## 🧰 Requirements

Install the following Python libraries:

```bash
pip install opencv-python mediapipe pynput  
```

## 🚀 How to Run

1️⃣ **Clone this repository:**
```bash
git clone https://github.com/your-username/gesture-car-control.git
cd gesture-car-control
```

2️⃣ **Show your hand in front of the webcam::**  
```bash
python hand_gesture_car_control.py
```

3️⃣ **Run the application**  
🖐️ All fingers open → Accelerate

✊ All fingers closed → Brake

4️⃣ **Press Q to quit the program.**



## 🖥️ How It Works  

📷 Webcam captures your hand in real-time.

🧠 MediaPipe processes hand landmarks.

✋ It checks the status of your fingers (open or closed).

⌨️ Based on the gesture, it simulates Left or Right arrow key presses using pynput.


## 📌 Notes 
• Only one hand is detected (the last detected hand is used).

• Make sure your background is clear and well-lit.

• The key press simulation works best in games or apps that support keyboard input directly. 


## 🧠 Future Ideas 
🔄 Add support for multiple gestures (turning, horn, gear shift)

🎯 Calibrate hand position to improve accuracy

🧪 Add feedback or haptic support

