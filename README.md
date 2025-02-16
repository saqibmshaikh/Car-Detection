# 🚗 YOLOv8 Car Detection

This project uses **YOLOv8 (You Only Look Once)** for real-time car detection from images and videos. YOLOv8 is a state-of-the-art deep learning model for object detection.

## 📌 Features
- Real-time car detection in images & videos
- Uses Ultralytics' **YOLOv8 model**
- Can process webcam feeds or video files
- Generates **bounding boxes** around detected carspython detect.py --image p
- ath/to/image.jpg

- Easy to deploy and modify

---

## 🛠 Installation & Setup

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/saqibmshaikh/Car-Detection.git
cd Car-Detection
Install Dependencies
pip install ultralytics opencv-python numpy matplotlib
from ultralytics import YOLO
model = YOLO('yolov8n.pt')  # Downloads the pre-trained YOLOv8 model
python detect.py --video path/to/video.mp4
Ultralytics YOLOv8
OpenCV



