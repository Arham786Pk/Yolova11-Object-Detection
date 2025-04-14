🧠 Real-Time Object Detection using YOLOv11
📌 Project Overview
This project demonstrates a real-time object detection system using YOLOv11 (You Only Look Once), integrated with a local webcam via OpenCV. The model performs real-time inference on live video frames, detects objects, and overlays bounding boxes with class labels in a smooth video feed.

🎯 Key Features
📷 Live webcam integration using OpenCV

🧠 YOLOv11 inference for real-time object detection

🔲 Bounding boxes and labels drawn directly on the video feed

🖥️ Runs on local CPU, no GPU required

🛑 Press 'q' to quit the live stream at any time

⚙️ Technologies Used
Python 3

Ultralytics YOLOv11 (via ultralytics library)

OpenCV for video capture and visualization

Matplotlib (optional for static image display)

🚀 How It Works
The webcam captures a live video stream frame by frame.

Each frame is passed to the YOLOv11 model for object detection.

Detected objects are annotated with bounding boxes and class labels.

The annotated frames are displayed in real time in a pop-up window.

