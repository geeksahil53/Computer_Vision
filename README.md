# Real-Time Hand Tracking using MediaPipe and OpenCV

This project demonstrates real-time hand tracking using **MediaPipe** and **OpenCV**. It captures video from your webcam and identifies 21 hand landmarks, drawing the connections on screen in real time.

---

**Requirements**

- Python 3.6 or higher  
- OpenCV  
- MediaPipe  

Install the required dependencies:

```bash
pip install opencv-python mediapipe
How to Run

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/hand-tracking.git
cd hand-tracking
Run the script:

bash
Copy
Edit
python hand_tracking.py
Press q to exit the application.

How It Works

Captures webcam feed using OpenCV.

Converts each frame to RGB format.

Processes the frame with MediaPipe's Hands model.

Draws 21 hand landmarks and their connections using MediaPipe's drawing utilities.

Displays the annotated video in real time.

Project Structure

bash
Copy
Edit
hand-tracking/
├── hand_tracking.py        # Main script
├── README.md               # Project documentation
└── requirements.txt        # (Optional) Dependency list
Features

Real-time hand landmark tracking

21-point hand detection with MediaPipe

Lightweight and easy to modify

Compatible with most webcams

Future Improvements

Gesture classification (e.g., thumbs up, peace sign)

Integration with virtual input systems

Logging hand coordinates for training custom model
