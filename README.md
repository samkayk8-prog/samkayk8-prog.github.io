# samkay.github.io
Samuel's Engineering Portfolio
# Tello Drone Navigation with OpenCV

This project enables a Tello drone to be navigated using computer vision and machine learning techniques. The system is built with **Python** and **OpenCV**.

![IMG_5118](https://github.com/user-attachments/assets/e5a3c440-f6dd-4bb4-a04f-c5512b0d9116)

## 🎯 Project Goals

This project was developed as part of the University of Windsor's Elevate program  and aims to achieve two primary navigation methods:

### 1. Point and Click Flying
* Captures the drone's live video feed in a window.
* Detects mouse-click coordinates within that video feed.
* Translates those coordinates into flight commands, telling the Tello drone to fly to the selected location.

### 2. ArUco Marker Tracking
* Uses the `OpenCV contrib` module to detect and identify ArUco markers (which function like QR codes).
* The algorithm draws boundaries, determines the center of the detected marker, and identifies its unique ID.
* This information is used to command the Tello drone to actively track and follow the marker in real-time.

## 🛠️ Technologies Used

* **Drone:** Tello
* **Core Library:** OpenCV (`cv2`)
* **Tracking Module:** `OpenCV contrib` (for ArUco detection)
* **Language:** Python

## Usage

(Here you should explain how to run your code)

1.  Clone the repository:
    ```bash
    git clone [your-repo-link]
    ```
2.  Install dependencies:
    ```bash
    pip install opencv-python opencv-contrib-python [any-other-libs]
    ```
3.  Run the main script:
    ```bash
    python track_marker.py
    ```

## Project Status
* [ ] Point and Click Flying
* [ ] ArUco Marker Detection
* [ ] Drone Follow/Tracking Logic
