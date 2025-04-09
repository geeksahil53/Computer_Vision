This project demonstrates real-time hand tracking using MediaPipe and OpenCV. It captures video from your webcam and identifies 21 hand landmarks, drawing the connections live on screen.

<!-- Replace with your own screen recording if available -->

📦 Requirements
Python 3.6+

OpenCV

MediaPipe

Install dependencies using:

bash
Copy
Edit
pip install opencv-python mediapipe
🚀 How to Run
Clone the repository and run the Python script:

bash
Copy
Edit
python hand_tracking.py
Press q to quit the program.

🧠 How It Works
The webcam feed is read using OpenCV.

Each frame is processed using MediaPipe's Hands solution.

Detected hand landmarks are drawn using MediaPipe's drawing_utils.

The program runs in a loop until the user presses the q key.

📂 File Structure
bash
Copy
Edit
hand-tracking/
│
├── hand_tracking.py        # Main Python script
├── README.md               # Project documentation
└── requirements.txt        # Optional: Python dependencies
🛠️ Features
Real-time hand detection

21-point hand landmark tracking

Simple and lightweight

Works on most systems with a webcam

🧩 Future Improvements
Add gesture recognition (e.g., thumbs up, peace sign)

Integrate with virtual mouse or keyboard input

Save hand position data for training models

📸 Preview
<!-- Replace with a screenshot of your app in action -->
