# Face Key Points Detection with MediaPipe

This project uses OpenCV and MediaPipe to perform face mesh detection on live video input from a webcam. It detects facial landmarks and draws them on the video feed in real-time.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

This script captures video from a webcam, detects facial landmarks using MediaPipe's Face Mesh solution, and draws the detected landmarks on the video feed. The script is capable of detecting multiple faces simultaneously and visualizes different face mesh connections with distinct styles.

## Installation

To run this project, ensure you have the following packages installed:

- OpenCV
- MediaPipe

You can install the required packages using pip:

```sh
pip install opencv-python mediapipe
```

## Usage

1. Clone the repository:

```sh
git clone https://github.com/yourusername/face-mesh-detection.git
cd face-mesh-detection
```

2. Run the script:

```sh
python face_mesh_detection.py
```

3. To exit the video feed, press the 'q' key.
