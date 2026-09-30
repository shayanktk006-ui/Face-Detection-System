# Face Detection System with OpenCV and YuNet

## Project Overview

A real-time face detection system built with OpenCV and YuNet.
The system detects faces from images and webcam frames, draws
bounding boxes and facial landmarks, displays confidence scores,
and captures processed images.

## Features

- Face detection using YuNet
- Real-time webcam face detection
- Bounding box visualization
- Five facial landmark detection
- Confidence score display
- Face count display
- Image-based face detection
- Webcam photo capture
- Processed image saving

## Technologies Used

- Python
- OpenCV
- NumPy
- YuNet Face Detection
- ONNX

## Installation

Clone the repository and install the required dependencies:

```bash
pip install -r requirements.txt

## How to Run

Run the face detection system with:

```bash
python face_detection.py

## Project Structure

```text
05_Face_Detection_Project/
├── Face_Detection_System.ipynb
├── face_detection.py
├── face_detection_yunet_2026may.onnx
├── ayanfriendpic.jpeg
├── face_detection_result.jpg
├── webcam_capture_result.jpg
├── requirements.txt
└── README.md

## Model

This project uses the YuNet face detection model in ONNX format.

YuNet is a lightweight deep learning model designed for efficient
face detection and facial landmark localization.

The model detects:
- Face bounding boxes
- Five facial landmarks
- Detection confidence

## Detection Pipeline

```text
Webcam / Image
       ↓
Frame Capture
       ↓
YuNet Face Detection
       ↓
Confidence Filtering
       ↓
Bounding Boxes + Landmarks
       ↓
Processed Output
       ↓
Save / Display Result

## Output

The system produces an annotated image containing:

- Detected face bounding boxes
- Facial landmarks
- Confidence scores
- Total number of detected faces

Captured results are saved as image files for further use.

## Future Improvements

- Face recognition
- Multi-person tracking
- Performance optimization
- Real-time FPS monitoring
- Web-based camera interface