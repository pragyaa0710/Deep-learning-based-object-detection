📌 Project Overview
This project is a real-time computer vision application that detects objects from a webcam feed using YOLOv3 and performs additional analysis such as gender recognition for persons and dominant color identification for other objects, leveraging deep learning models.

🎯 Objective
To build a real-time deep learning system that detects objects, identifies human gender, and recognizes dominant object colors from live video input.

🛠️ Tech Stack
Python, OpenCV (DNN module), YOLOv3, NumPy, Google Colab, JavaScript (Webcam bridge)

🧩 Models Used
YOLOv3 – Object detection (COCO dataset)
Caffe Gender Classification Model – Gender prediction for detected persons

⚙️ How the System Works
Captures live video frames using a JavaScript–Python bridge in Google Colab
Detects objects in each frame using YOLOv3
Applies Non-Maximum Suppression to remove duplicate detections
If the detected object is a person, predicts gender using a deep learning model
If the detected object is non-human, extracts the dominant color using K-means clustering
Displays bounding boxes with object labels, gender, or color in real time

🚀 Key Features
Real-time object detection from webcam
Gender classification for detected persons
Dominant color recognition for objects
GPU acceleration support (CUDA if available)
Modular and extensible deep learning pipeline

📂 Files Downloaded Automatically
yolov3.weights
yolov3.cfg
coco.names
gender_net.caffemodel
deploy_gender2.prototxt

▶️ How to Run
Open the notebook in Google Colab
Run all cells sequentially
Allow webcam access when prompted
Observe real-time detections on the video feed

📈 Use Cases
Smart surveillance systems
Human-centered AI applications
Retail analytics
Human–computer interaction projects

🔮 Future Enhancements
Age detection integration
Object tracking across frames

Performance optimization for edge devices

Web or mobile deployment
