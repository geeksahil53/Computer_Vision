# Real-Time Hand Tracking using MediaPipe and OpenCV

This repository contains a computer vision project that uses **MediaPipe** and **OpenCV** to detect and track hands in real time via a webcam feed. It utilizes MediaPipe's `Hands` solution to identify 21 hand landmarks and draw connections between them for visualization.

## Contents

- **hand_tracking.py:**
  - Main Python script that captures video from a webcam, detects hands in each frame, and visualizes the hand landmarks and their connections.
  - Utilizes OpenCV for camera input and display, and MediaPipe for hand landmark detection.

- **README.md:**
  - Project documentation and usage guide.

- **requirements.txt (optional):**
  - List of required Python packages (`opencv-python`, `mediapipe`).

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/hand-tracking.git
    cd hand-tracking
    ```

2. Install the required Python packages:

    ```bash
    pip install opencv-python mediapipe
    ```

## Usage

1. Run the hand tracking script:

    ```bash
    python hand_tracking.py
    ```

2. A window will open displaying your webcam feed with hand landmarks visualized.

3. Press the `q` key to quit the application.

## How It Works

- The script opens a webcam feed using OpenCV.
- Each frame is converted from BGR to RGB and passed to MediaPipe’s `Hands` model.
- If a hand is detected, MediaPipe returns 21 hand landmarks.
- The script then draws these landmarks and the skeletal connections between them on the frame using MediaPipe's drawing utilities.
- The processed frame is displayed in real time until the user exits.

## Acknowledgments

- This project uses the **MediaPipe Hands** solution by Google, which provides highly accurate and fast hand detection.
- OpenCV is used for image handling and visualization.
- Inspired by real-time gesture-based interfaces and applications in HCI (Human-Computer Interaction).

