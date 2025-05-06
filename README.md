# 🎮🕺NeuRun : Pose-Controlled Endless Runner Game

This project demonstrates an innovative way to control a Subway Surfer-like game using **body movements** captured through a webcam. By combining **computer vision** and **pose detection**, players can navigate the game hands-free, making it both fun and interactive!

## 🧠 Technologies Used

- Python  
- OpenCV  
- MediaPipe  
- PyAutoGUI  
- Matplotlib (for debugging/visualization)

## 💡 How It Works

- Uses **MediaPipe** to detect full-body pose in real-time.
- Maps key body movements to specific **arrow key inputs**:
  - 🏃 **Left** → Move body to the left  
  - 🏃 **Right** → Move body to the right  
  - 🪂 **Jump** → Jump in real life  
  - 🧎 **Crouch** → Bend or squat down
- Uses **OpenCV** to access your webcam and display tracking.
- Simulates key presses using **PyAutoGUI** for game control.
- Starts the game with a **"join hands"** gesture.

## 🔧 Features

- 🎮 Control the game entirely using **body gestures**.
- 🚫 No keyboard or mouse required during gameplay.
- 🕵️‍♂️ Real-time pose tracking with visual feedback.
- 🤸 Responsive movement detection using upper and lower body positions.

## ✨ Future Improvements

- 🔄 Add more gesture-based controls (e.g., swipe, turn).
- 🕹️ Support for other popular games using the same pose interface.
- ⚡ Performance optimization and reduced latency.
- 📱 Possible mobile camera support over network.

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/PoseControlled-SubwaySurfer.git
cd PoseControlled-SubwaySurfer
pip install -r requirements.txt
python neurun.py
