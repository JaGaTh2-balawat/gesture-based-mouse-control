AI Hand Gesture Mouse Control
Control your computer cursor using hand gestures—no physical mouse needed!
This project uses OpenCV + MediaPipe + PyTorch to track hand landmarks and translate them into mouse actions in real-time.
🚀 Features
Gesture	Action
Move Index Finger	Move Mouse Cursor
Thumb + Index PIP near	✅ Single Click
Thumb + Middle Finger near	✅ Right Click
Index + Middle close	✅ Scroll Up
Thumb + Ring Finger close	✅ Scroll Down
Thumb + Index Tip near	✅ Click & Drag (Press/Release)
Index Tip + Middle Tip	✅ Double Click
✅ Real-time webcam detection
✅ Visual hand landmark overlay
✅ Smooth cursor control
✅ Gestures mapped to OS mouse events
✅ Saves recording as out.avi
🧠 Tech Stack
Python
OpenCV – Webcam video processing
MediaPipe Hands – Finger landmarks detection
PyTorch – CNN placeholder for future gesture learning
NumPy – Calculating distances between landmarks
Tkinter – Screen size detection
mouse Python library – Mouse input control

⏬ Installation
pip install opencv-python mediapipe torch torchvision mouse numpy tk

🏃‍♂️ Usage
cd GestureBasedMouseControl
python main.py


Use your hand gestures inside the red rectangle to control the mouse.

Press ESC to exit the program.

🔖 Keywords

python, opencv, mediapipe, hand-tracking, computer-vision, mouse-control, gesture-control, pytorch, ai-mouse, gesture-recognition, cv-project, assistive-technology, human-computer-interaction, deep-learning
